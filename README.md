# powermanage - bash-script

Little script that I use for my power management.
It opens an urxvt-Terminal (can be changed) with a bash-script that asks if you want to power off, reboot or hibernate.

![Example Image of the menu](https://raw.githubusercontent.com/bowbored/powermanage/main/powermenu.jpg)

# How to use it

Both Files (power and powermanage) have to be executable.
```
chmod +x power
chmod +x powermanage
```

Copy the files to /usr/bin/
```
sudo cp power /usr/bin/
sudo cp powermanage /usr/bin/
```

Then you can assign "powermanage" to a shortcut.
I used mod+0 and wrote it into my i3 config file. How you can do this depends on your Distro (or wm).
