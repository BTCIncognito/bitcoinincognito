
Debian
====================
This directory contains files used to package btcid/btci-qt
for Debian-based Linux systems. If you compile btcid/btci-qt yourself, there are some useful files here.

## btci: URI support ##


btci-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install btci-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your btciqt binary to `/usr/bin`
and the `../../share/pixmaps/btci128.png` to `/usr/share/pixmaps`

btci-qt.protocol (KDE)

