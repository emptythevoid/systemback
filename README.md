# Systemback for Ubuntu

This is a repository for the latest version of Systemback for Ubuntu.  
Systemback has been abandoned by it's author, so you use this software at your own risk.
I provide no guarantees that this will work.
I provide no guarantees that this won't break your computer.

## A note about the original package

The original Systemback tar.xz file contained an install.sh file that would attempt to detect
which release you were using. This script has never been updated for newer versions of Ubuntu.
This repackaging I've created skips the install script entirely.

## Getting Started

First, open a terminal and make sure your apt cache is up to date

sudo apt update

Second, install dependencies using this command:

sudo apt install libqt5core5a casper live-boot isolinux syslinux-utils libqt5gui5 libqt5widgets5 xterm

Third, download the .zip file and extract it.  Navigate to it and run this command to install all the deb files:

sudo dpkg -i ./*.deb

## Video Walkthrough
[https://www.youtube.com/watch?v=eUzqFv4LaC8]

