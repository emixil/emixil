
Debian
====================
This directory contains files used to package emixild/emixil-qt
for Debian-based Linux systems. If you compile emixild/emixil-qt yourself, there are some useful files here.

## emixil: URI support ##


emixil-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install emixil-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your emixil-qt binary to `/usr/bin`
and the `../../share/pixmaps/emixil128.png` to `/usr/share/pixmaps`

emixil-qt.protocol (KDE)

