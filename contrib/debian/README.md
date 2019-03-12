
Debian
====================
This directory contains files used to package XVGDGd/XVGDG-qt
for Debian-based Linux systems. If you compile XVGDGd/XVGDG-qt yourself, there are some useful files here.

## XVGDG: URI support ##


XVGDG-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install XVGDG-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your XVGDGqt binary to `/usr/bin`
and the `../../share/pixmaps/XVGDG128.png` to `/usr/share/pixmaps`

XVGDG-qt.protocol (KDE)

