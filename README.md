# spenny-dwm

![screenshot of spenny-dwm](http://imgur.com/MxLSkCE)

This is my personal configuration of dwm by suckless (https://dwm.suckless.org/), with a colorscheme inspired by Evangelion Unit 01. The config.mk file is set up to compile on FreeBSD, A simplified version of dwm-sss by joeiddon (https://github.com/joeiddon/dwm_sss) is included to display the clock. This script has been modified to run under zsh, so if you use bash or another terminal editor be sure to change the top line to your relevant shell path. 

# setup
## required packages
+ dbus
+ xorg-minimal
+ libXft
+ libXinerama
+ powerline-fonts
+ sterm
+ dmenu

If you're using FreeBSD, you should be able to simply clone this repository and run "sudo make clean install" right out of the box. If you're on Linux or any other alternative you may need to change config.mk to suit your needs. Once installed, simply add the included .xinitrc file to your home directory and restart your X server.  
