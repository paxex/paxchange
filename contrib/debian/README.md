
Debian
====================
This directory contains files used to package paxchanged/paxchange-qt
for Debian-based Linux systems. If you compile paxchanged/paxchange-qt yourself, there are some useful files here.

## paxchange: URI support ##


paxchange-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install paxchange-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your paxchangeqt binary to `/usr/bin`
and the `../../share/pixmaps/paxchange128.png` to `/usr/share/pixmaps`

paxchange-qt.protocol (KDE)

