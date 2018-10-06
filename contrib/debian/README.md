
Debian
====================
This directory contains files used to package dashd/bcash-qt
for Debian-based Linux systems. If you compile dashd/bcash-qt yourself, there are some useful files here.

## bcash: URI support ##


bcash-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install bcash-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your bcash-qt binary to `/usr/bin`
and the `../../share/pixmaps/dash128.png` to `/usr/share/pixmaps`

bcash-qt.protocol (KDE)
