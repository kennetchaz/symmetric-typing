Soul layout for macOS
====================================

The bundle contains keyboard layouts for both regular and **Extended** variants,
which are based on the built-in **ABC** and **ABC - Extended** layouts in macOS.

## Installing

To install, simply copy the `Soul.bundle` file to your `Keyboard Layouts` directory.
There are two possible `Keyboard Layouts` directories to choose from:

- `/Library/Keyboard Layouts` a.k.a `Macintosh HD > Library > Keyboard Layouts`  
  Installing to this directory will install the keyboard layout
  system-wide for all users. This is the preferred installation
  directory.
- `~/Library/Keyboard Layouts` a.k.a `Macintosh HD > Users > USERNAME > Library > Keyboard Layouts`  
  This is your personal user-local keyboard layouts directory. The
  easiest way to navigate there is to open a new Finder window, select
  `Go` from the top menu, hold the Option key on the keyboard and select
  the `Library` menu item. From there, if the `Keyboard Layouts` directory
  does not exist, you must make it yourself. Installing to this directory
  will install the keyboard layout for you only and not other users on the
  system. **Be warned!** Using the user-local installation directory does
  not allow the layout to be used in sensitive inputs like password entry
  dialogues; you may find that macOS will switch you off of your selected
  keyboard layout from time to time if it is installed here.

After installation, you may need to log out of your system and log back
in for the keyboard layout to become available in your System
Preferences.

To enable the installed keyboard layout, launch the System Preferences
app and navigate to Keyboard -> Input Sources and use the + button in
the bottom left corner of the pane to select your desired keyboard
layout. The newly installed keyboard layouts should be available in the
"English" section.

## Customization

If you'd like to customize these keyboard layouts, you can edit the XML
inside of the `.keylayout` files directly or, if obtuse XML isn't to
your liking, Ukelele is a graphical tool for editing these bundles.
Ukelele is available for download at https://software.sil.org/ukelele/.