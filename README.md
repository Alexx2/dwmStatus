dwm status bar
==============
created:  20.02.2014
modified: 20.02.2014

This is my take on the dwm window manager status bar. 

It is probably not much portable, but you can use as a reference for your own take on the bar. 

It makes use of the statuscolors patch for dwm and Tamsynmod font (for the cool icons). Both are dependencies
for this bar. 


Screenshot
----------

status bar on the right:

![dwm status bar](https://raw2.github.com/Alexx2/dwmbar/master/dwmbar_screenshot.png)


Compiling notes
---------------

To compile this status bar (using gcc, in the source code directory):

gcc -lX11 dwmbar.c -o dwmbar 


