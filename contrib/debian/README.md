
Debian
====================
This directory contains files used to package telserracoind/telserracoin-qt
for Debian-based Linux systems. If you compile telserracoind/telserracoin-qt yourself, there are some useful files here.

## telserracoin: URI support ##


telserracoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install telserracoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your telserracoinqt binary to `/usr/bin`
and the `../../share/pixmaps/telserracoin128.png` to `/usr/share/pixmaps`

telserracoin-qt.protocol (KDE)

