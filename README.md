I'm basing all my sway dotfiles on Luispabon's files. I shamelessly copied all of his files and then changed stuff so that it works better with my computer and my preferences. The original repo is [here](https://github.com/luispabon/sway-dotfiles)

# Sway dotfiles

This is my sway configuration, together with scripts and assets required to make it work.

## Install scripts

I use ubuntu 20.04, and as such any package installation stuff on the scripts are for ubuntu 20.04. I don't recommend you use these as they're tailored to my specific use case.

  * [install.sh](install.sh) installs all the apps and tools I use daily, sets up sway session on the system and any other work necessary for the whole thing to work.
  * [install_xps9560.sh](install_xps9560.sh) installs system services for things like extra powersaving, undervolt etc. Tailored to my specific system.

To make it all work you need to add `~/bin` to your path as some of the scripts install in there. You also need a build of waybar (again you can compile by yourself from the repo above).

## Notifications

Make sure you pull submodules as you'll need https://github.com/vlevit/notify-send.sh to make notifications work.

There are notification scripts for volume and brightness, and sway bindings for these on fn keys (but not waybar).


## TODO

 * terraform: install and move, symlink
