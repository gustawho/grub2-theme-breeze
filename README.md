# Breeze

A minimalistic GRUB theme inspired by Breeze.

![Preview](preview.jpg)

## Icons

![Shipped icons and logos](icons.png)

## Installation
Copy the "breeze" directory to a location GRUB can access it. The standard path is `/usr/share/grub/themes/`, but if your installing this theme in an encrypted system, you might prefer to copy this package content to `/boot` and set your GRUB configuration file accordingly.

Edit `/etc/default/grub`, making sure this line (or a variant of it) exists:

`GRUB_THEME="/usr/share/grub/themes/breeze/theme.txt"`

And then run:

`sudo grub-mkconfig -o /boot/grub/grub.cfg`
