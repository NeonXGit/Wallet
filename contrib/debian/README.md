
Debian
====================
This directory contains files used to package neonxd/neonx-qt
for Debian-based Linux systems. If you compile neonxd/neonx-qt yourself, there are some useful files here.

## neonx: URI support ##


neonx-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install neonx-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your neonx-qt binary to `/usr/bin`
and the `../../share/pixmaps/neonx128.png` to `/usr/share/pixmaps`

neonx-qt.protocol (KDE)

