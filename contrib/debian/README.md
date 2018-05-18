
Debian
====================
This directory contains files used to package iqcashd/iqcash-qt
for Debian-based Linux systems. If you compile iqcashd/iqcash-qt yourself, there are some useful files here.

## iqcash: URI support ##


iqcash-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install iqcash-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your iqcash-qt binary to `/usr/bin`
and the `../../share/pixmaps/iqcash128.png` to `/usr/share/pixmaps`

iqcash-qt.protocol (KDE)

