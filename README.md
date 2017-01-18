# jgd-spring-awakening

JGD-Spring Awakening is a collection of themes for the Linux desktop. Featuring a fresh and friendly design, each theme's main color scheme is a pastel yellow and bright green.

Included in this theme package are Openbox, GTK+2 and GTK+3 (currently version 3.10 only) themes.

The GTK+2 version requires the Murrine engine. Instructions on how to install Murrine are below.

## How to install this theme collection:

1. Download the file from the [Downloads] (https://github.com/jgpws/jgd-spring-awakening/blob/master/downloads/JGD-SpringAwakening-01-17-17.tar.gz) directory
2. Open a Terminal application
3. Navigate to your Downloads folder in the terminal (usually titled Downloads). Type **cd Downloads**
4. Type **ls** and look for **JGD-SpringAwakening-month-day-year.tar.gz**, where month, day and year represent when the file was last updated
5. Untar the file by typing **tar -zxvf JGD-SpringAwakening-01-01-17.tar.gz**, substituting the current version's date numbers
6. type **cd** again to get to your home folder; type **ls -a** and see if there is a **.themes** directory
7. If one does not exist, create one: **mkdir .themes**
8. **cd Downloads/JGD-SpringAwakening-month-day-year**
9. **cp JGD-SpringAwakening ../../.themes**

or to install globally

1. **cd /usr/share/themes**
2. **sudo cp ~/Downloads/JGD-SpringAwakening-month-day-year/JGD-SpringAwakening /usr/share/themes**
3. Enter sudo password
4. **ls** to check that the theme folder is present

If you prefer using a GUI for these purposes, as it is easier, do so. To install to usr/share/themes, run your file manager as sudo from the command line (for example: **gksudo pcmanfm**).

## How to install Murrine for GTK+2:

### Theme Engines installation for Ubuntu:**

In the **Ubuntu Software Center**, search for **Murrine**. Then you can select **Cairo-based gtk+-2.0 theme engine**, which has the package name gtk-engines-murrine.

### Theme Engines installation for Arch Linux:

**sudo pacman -S gtk-engines**

*Note: The GTK+3 theme has been tested so far only in a Gnome version 3.10 environment on Ubuntu LTS 14.04. Because of the nature of GTK theming, it is not guaranteed to render correctly in other versions.

To switch themes, you can use your desktop environment's theme switcher.

Enjoy!

I'm now currently using Arch Linux as my new operating system. In the future, for this theme, I will create an AUR package for auto install (as soon as I learn how to do so and after this theme has been updated for gtk 3.20+).
