ixkeylog
========

This is a X11 keylogger for Unix that basically uses xlib to interact with users
keyboard. IXKeyLog will listen for certain X11 events and then trigger specific
routines to handle these events. 

Type './ixkeylog -h' for full list of options.


Requirements
------------

    * gcc
    * make / gmake
    * Xlib: libX11 / libX11-dev
    
    
Compiling
------------

You won't need to compile the whole stuff by yourself. Just type 'make' in the
root directory of the package and you'll get the available make targets. Type:

        gmake -f Makefile.[put your OS here] ixkeylog

for compiling the main binary. Use

        gmake -f Makefile.[put your OS here] clean

to cleanup everything. 
    
