
Debian
====================
This directory contains files used to package blackbearcoind/blackbearcoin-qt
for Debian-based Linux systems. If you compile blackbearcoind/blackbearcoin-qt yourself, there are some useful files here.

## blackbearcoin: URI support ##


blackbearcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install blackbearcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your blackbearcoinqt binary to `/usr/bin`
and the `../../share/pixmaps/blackbearcoin128.png` to `/usr/share/pixmaps`

blackbearcoin-qt.protocol (KDE)

