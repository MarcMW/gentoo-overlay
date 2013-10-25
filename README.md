gentoo-overlay
==============

My personal gentoo portage overlay.

**x11-misc/xscreensaver:**   
added branding USE flag, changes flame logo to gentoo logo.



**Usage:**
copy `local.xml` to `/var/lib/layman/local.xml`  
edit `/etc/layman/layman.cfg` and  
add an overlay pointing to `file:///var/lib/layman/local.xml`
`layman -f`  
`layman -a muewei`  
