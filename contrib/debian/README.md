
Debian
====================
This directory contains files used to package bullishcoind/bullishcoin-qt
for Debian-based Linux systems. If you compile bullishcoind/bullishcoin-qt yourself, there are some useful files here.

## bullishcoin: URI support ##


bullishcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install bullishcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your bullishcoinqt binary to `/usr/bin`
and the `../../share/pixmaps/bullishcoin128.png` to `/usr/share/pixmaps`

bullishcoin-qt.protocol (KDE)

