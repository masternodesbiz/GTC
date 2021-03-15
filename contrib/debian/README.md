
Debian
====================
This directory contains files used to package gastrocoind/gastrocoin-qt
for Debian-based Linux systems. If you compile gastrocoind/gastrocoin-qt yourself, there are some useful files here.

## gastrocoin: URI support ##


gastrocoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install gastrocoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your gastrocoinqt binary to `/usr/bin`
and the `../../share/pixmaps/gastrocoin128.png` to `/usr/share/pixmaps`

gastrocoin-qt.protocol (KDE)

