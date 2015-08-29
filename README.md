# Breeze
A minimalistic GRUB theme inspired by Breeze

![Default view](http://opendesktop.org/CONTENT/content-pre1/171217-1.png)
![Available distro logos](http://opendesktop.org/CONTENT/content-pre2/171217-2.png)

## Installation
As root, 
```bash
# git clone https://github.com/gustawho/grub2-theme-breeze /boot/grub/themes/breeze
```

Then edit /etc/default/grub:
```bash
GRUB_THEME="/usr/share/grub/themes/breeze/theme.txt"
```

Re-generate grub.cfg to apply the changes:
```bash
# grub-mkconfig -o /boot/grub/grub.cfg
```

If configuring the theme was successful, you will see Found theme: /usr/share/grub/themes/breeze/theme.txt in the terminal.
