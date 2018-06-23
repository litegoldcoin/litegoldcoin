
Debian
====================
This directory contains files used to package litegoldcoind/litegoldcoin-qt
for Debian-based Linux systems. If you compile litegoldcoind/litegoldcoin-qt yourself, there are some useful files here.

## litegoldcoin: URI support ##


litegoldcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install litegoldcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your litegoldcoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/litegoldcoin128.png` to `/usr/share/pixmaps`

litegoldcoin-qt.protocol (KDE)

