To try the solemak layout on Linux you can use the `xmodmap` definition in this
folder. Just try this command and keep your Solemak cheatsheet near you:

    $ xmodmap solemak.xmodmap

The solemak layout will last only for the current session, when you
will restart your computer you will have your usual layout.

If you want to have a more permanent setup than you can use the xkb definition
file (it's just named `solemak`) and put it in your xkb symbols folder, which
depends on your distribution.  In my case, since I'm using fedora in this
moment, the right location is:

    /usr/share/X11/xkb/symbols

When you have put the file in the right location you can just:

    $ setxkbmap solemak

Even this setting will last only for the current session. The command to make
the layout the default one depends on your distribution.
