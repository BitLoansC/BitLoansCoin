
Debian
====================
This directory contains files used to package bitloanscoind/bitloanscoin-qt
for Debian-based Linux systems. If you compile bitloanscoind/bitloanscoin-qt yourself, there are some useful files here.

## bitloanscoin: URI support ##


bitloanscoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install bitloanscoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your bitloanscoinqt binary to `/usr/bin`
and the `../../share/pixmaps/bitloanscoin128.png` to `/usr/share/pixmaps`

bitloanscoin-qt.protocol (KDE)

