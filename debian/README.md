
Debian
====================
This directory contains files used to package aixd/aix-qt
for Debian-based Linux systems. If you compile aixd/aix-qt yourself, there are some useful files here.

## aix: URI support ##


aix-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install aix-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your aix-qt binary to `/usr/bin`
and the `../../share/pixmaps/aix128.png` to `/usr/share/pixmaps`

aix-qt.protocol (KDE)

