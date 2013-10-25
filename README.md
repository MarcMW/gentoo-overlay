gentoo-overlay
==============

my personal gentoo portage overlay

x11-misc/xscreensaver:  
added branding USE flag, if applied patch changes flame to a gentoo logo.



Usage:

copy local.xml to /var/lib/layman/local.xml  
add overlay local.xml to /etc/layman/layman.cfg  
layman -f  
layman -a muewei  
