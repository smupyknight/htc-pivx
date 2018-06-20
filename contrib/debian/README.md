
Debian
====================
This directory contains files used to package thcd/thc-qt
for Debian-based Linux systems. If you compile thcd/thc-qt yourself, there are some useful files here.

## thc: URI support ##


thc-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install thc-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your thcqt binary to `/usr/bin`
and the `../../share/pixmaps/thc128.png` to `/usr/share/pixmaps`

thc-qt.protocol (KDE)

