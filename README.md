# nobinutils

Simply here to satisfy the unnecessary binutils dependency for mkinitcpio.

mkinitcpio uses objcopy from binutils to build a UKI (Unified Kernel Image), which is not enabled by default.

binutils is a 40 MiB collection of dev tools and is dragged in for every linux install through mkinitcpio.

It should have been made an optdepends.

I've [complained](https://gitlab.archlinux.org/archlinux/mkinitcpio/mkinitcpio/-/issues/212) but that has been ignored.

The authors don't seem to give a crap about dependency creep and bloat. Boo.
