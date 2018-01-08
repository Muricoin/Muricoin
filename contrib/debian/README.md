
Debian
====================
This directory contains files used to package muricoind/muricoin-qt
for Debian-based Linux systems. If you compile muricoind/muricoin-qt yourself, there are some useful files here.

## muricoin: URI support ##


muricoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install muricoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your muricoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoin128.png` to `/usr/share/pixmaps`

muricoin-qt.protocol (KDE)

