# jgd-spring-awakening

JGD-Spring Awakening is a collection of themes for the Linux desktop. Featuring a fresh and friendly design, each theme's main color scheme is a pastel yellow and bright green.

* [Theme homepage](http://www.jasong-designs.com/2016/08/12/jgd-spring-awakening-gtk/)

Included in this theme package are Openbox, GTK+2 and GTK+3 (versions 3.10 and 3.20 only) themes.

The GTK+2 version requires the Murrine engine. Instructions on how to install Murrine are below.

## How to install this theme collection:

1. Download the latest file from the [Downloads](https://github.com/jgpws/jgd-spring-awakening/blob/master/downloads/) directory
2. Open a Terminal application
3. Navigate to your Downloads folder in the terminal (usually titled Downloads). Type `cd Downloads`
4. Type `ls` and look for **JGD-SpringAwakening-month-day-year.tar.gz** (newer versions are all lowercased letters), where month, day and year represent when the file was last updated
5. Untar the file by typing `tar -zxvf JGD-SpringAwakening-01-01-17.tar.gz`, substituting the current version's date numbers
6. type `cd` again to get to your home folder; type `ls -a` and see if there is a **.themes** directory
7. If one does not exist, create one: `mkdir .themes`
8. `cd Downloads`
9. `cp JGD-SpringAwakening ../.themes`

### To Install Globally

1. `cd /usr/share/themes`
2. `sudo cp ~/Downloads/JGD-SpringAwakening /usr/share/themes`
3. Enter sudo password
4. `ls` to check that the theme folder is present

If you prefer using a GUI for these purposes, as it is easier, do so. To install to usr/share/themes, run your file manager as sudo from the command line (for example: `gksudo pcmanfm`).

### To Install on Arch Linux

JGD-Spring Awakening can be installed from the Arch User Repository via a package helper, such as [Yay](https://github.com/Jguer/yay):

```yay -S jgd-springawakening```

## How to Install Murrine for GTK+2:

### Theme Engines Installation for Ubuntu:

In the **Ubuntu Software Center**, search for **Murrine**. Then you can select **Cairo-based gtk+-2.0 theme engine**, which has the package name gtk-engines-murrine.

### Theme Engines installation for Arch Linux:

```sudo pacman -S gtk-engines```

*Note: The GTK+3 theme has been tested in Gnome version 3.10 environment on Ubuntu LTS 14.04 and version 3.22 on Arch Linux. Because of the nature of GTK theming prior to version 3.20, it is not guaranteed to render correctly in versions below 3.20.

To switch themes, you can use your desktop environment's theme switcher.

Enjoy!
