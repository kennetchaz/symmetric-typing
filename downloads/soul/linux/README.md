To try the Soul layout on Linux you can use the `xmodmap` definition in this
folder. 

    $ xmodmap soul.xmodmap

The Soul layout will last only for the current session, when you
will restart your computer you will have your usual layout.

If you want to have a more permanent setup than you can use the xkb definition
file (it's just named `soul`) and put it in your xkb symbols folder, which
depends on your distribution.  In my case, since I'm using fedora in this
moment, the right location is:

    /usr/share/X11/xkb/symbols

When you have put the file in the right location you can just:

    $ setxkbmap soul

Even this setting will last only for the current session. The command to make
the layout the default one depends on your distribution.
