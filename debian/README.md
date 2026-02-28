
Debian
====================
This directory contains files used to package aixcoind/aixcoin-qt
for Debian-based Linux systems. If you compile aixcoind/aixcoin-qt yourself, there are some useful files here.

## aixcoin: URI support ##


aixcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install aixcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your aixcoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/aixcoin128.png` to `/usr/share/pixmaps`

aixcoin-qt.protocol (KDE)

