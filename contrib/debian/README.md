
Debian
====================
This directory contains files used to package belled/belle-qt
for Debian-based Linux systems. If you compile belled/belle-qt yourself, there are some useful files here.

## pivx: URI support ##


belle-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install belle-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your belle-qt binary to `/usr/bin`
and the `../../share/pixmaps/pivx128.png` to `/usr/share/pixmaps`

belle-qt.protocol (KDE)
