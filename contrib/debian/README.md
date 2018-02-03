
Debian
====================
This directory contains files used to package cupd/cup-qt
for Debian-based Linux systems. If you compile cupd/cup-qt yourself, there are some useful files here.

## cup: URI support ##


cup-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install cup-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your cup-qt binary to `/usr/bin`
and the `../../share/pixmaps/cup128.png` to `/usr/share/pixmaps`

cup-qt.protocol (KDE)

