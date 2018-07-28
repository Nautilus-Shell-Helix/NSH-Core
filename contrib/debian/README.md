
Debian
====================
This directory contains files used to package nshcd/nshc-qt
for Debian-based Linux systems. If you compile nshcd/nshc-qt yourself, there are some useful files here.

## nshc: URI support ##


nshc-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install nshc-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your nshc-qt binary to `/usr/bin`
and the `../../share/pixmaps/nshc128.png` to `/usr/share/pixmaps`

nshc-qt.protocol (KDE)

