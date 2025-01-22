# BasiliskII-Port
FreeBSD Port of BasiliskII

## Synopsys 
Originally I wanted to see if i could resurect the FreeBSD Port of BasiliskII from FreeBSD 8.2 .
In hunting around for other gits on how to build and run it , I ran into this one https://github.com/ekbann/rpi-basilisk2-sdl2-nox .

Using the version noted in this git I was able to build BasiliskII via this port. 

I am hosting a git checkout of the upstream version at http://mirrors.nycbug.org .

## Status
The port builds and runs fine on FreeBSD 14.x amd64. I was not able to get it to build correctly on arm64 . BasiliskII's core 
needs a update on how to handle arm cpus on FreeBSD.

This port works under X11 , I have not tried to figure out how to make it work via console mode yet. 

![image](https://github.com/user-attachments/assets/38006084-c93f-4fb9-9f0c-1e2e54faded7)
