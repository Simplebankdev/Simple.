
Debian
====================
This directory contains files used to package simpled/simple-qt
for Debian-based Linux systems. If you compile simpled/simple-qt yourself, there are some useful files here.

## simple: URI support ##


simple-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install simple-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your simple-qt binary to `/usr/bin`
and the `../../share/pixmaps/simple128.png` to `/usr/share/pixmaps`

simple-qt.protocol (KDE)

