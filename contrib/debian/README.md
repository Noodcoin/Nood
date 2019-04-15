Debian
======

This directory contains files used to package noodd/nood-qt
for Debian-based Linux systems. If you compile noodd/nood-qt yourself, there are some useful files here.

## nood: URI support ##

nood-qt.desktop (Gnome / Open Desktop)

To install:

	sudo desktop-file-install nood-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your nood-qt binary to `/usr/bin`
and the `../../share/pixmaps/nood128.png` to `/usr/share/pixmaps`

nood-qt.protocol (KDE)