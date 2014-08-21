
Debian
====================
This directory contains files used to package tradercoind/tradercoin-qt
for Debian-based Linux systems. If you compile tradercoind/tradercoin-qt yourself, there are some useful files here.

## tradercoin: URI support ##


tradercoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install tradercoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your tradercoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/tradercoin128.png` to `/usr/share/pixmaps`

tradercoin-qt.protocol (KDE)

