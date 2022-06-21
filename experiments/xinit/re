~/.xinitrc
```
# 
# This file is sourced when running startx and other programs which call xinit

# Set background to your favorite pic
xsetbg -fullscreen /home/chronos/wallpapers/wallpaper.png &

# Start a Chromium Platform can be replaced by chromium-browser but as chromiumOS short chronos uses wayland 
# we are maybe able to skip the window-manager as we do not need to show any close and title dialogs.
# but maybe we need it to integrate with other notification providers from eg: gnome
/home/chronos/bin/chronos &

# > --ash-default-guest-wallpaper-large
# > --ash-default-guest-wallpaper-small
# > --ash-default-wallpaper-large
# > --ash-default-wallpaper-small

# Start the systems window manager. See WindowManagers for other choices.
exec /etc/alternatives/x-window-manager

# To run Gnome instead of system default, place a 
# '#' before the previous line and uncomment the 
# next line.
# exec gnome-session
```
