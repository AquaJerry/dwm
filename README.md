# Dynamic window manager for X display server

Forked from official https://dwm.suckless.org.

This dwm provides a simple user interface for me to focus on apps themselves.


## Thanks

- suckless.org e.V., München, Germany, who make softwares that suck less


## Used patches

In terminal below have been 'patch < \*.diff'.

- dwm.suckless.org/patches/fakefullscreen
- dwm.suckless.org/patches/notitle


## Differences from official dwm

config.def.h:

- 2 tags in total (9 official)
- half divide screen in tile layout
- hide topbar at start
- monocle layout at start (tile layout official)
- no window border

dwm.c:

- no default dwm-VERSION status text
