
Debian
====================
This directory contains files used to package blxd/blx-qt
for Debian-based Linux systems. If you compile blxd/blx-qt yourself, there are some useful files here.

## blx: URI support ##


blx-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install blx-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your blxqt binary to `/usr/bin`
and the `../../share/pixmaps/blx128.png` to `/usr/share/pixmaps`

blx-qt.protocol (KDE)

