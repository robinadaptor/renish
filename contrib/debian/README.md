
Debian
====================
This directory contains files used to package renishd/renish-qt
for Debian-based Linux systems. If you compile renishd/renish-qt yourself, there are some useful files here.

## renish: URI support ##


renish-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install renish-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your renish-qt binary to `/usr/bin`
and the `../../share/pixmaps/renish128.png` to `/usr/share/pixmaps`

renish-qt.protocol (KDE)

