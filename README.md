afpfs-ng-fork
=============

afpfs-ng is an Apple Filing Protocol client that will allow BSD, 
Linux and Mac OS X systems to access files exported from a Mac OS 
system with AFP over TCP. 

Forked from http://sourceforge.net/projects/afpfs-ng.

I forked this package to make it work on RaspberryPi 
together with XBMC, Apple Airport Extreme Shared Disks 
and autofs/automount, because performance with media 
mounts via cifs were way too slow to playback high-resolution
video files.

afp vs. cifs gives you a four times better performance
on the same hardware.
