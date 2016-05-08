#Yum Extract

This is a small program that finds packages from yum, downloads them via yumdownloader and extracts them to a chosen directory.
The purpose of this is for local installs of packages available on yum without root access.

##Requirements
* yumdownloader
* yum
* python3 (>3.3)

The program was tested on RHEL 7 - not sure how it works on other distributions yet.

##Usage

Used by executing the program and specifying the package. For example:
```bash
./yumextract -i686 freetype
```
would install the 32 bit version of the freetype package in the current working directory.
