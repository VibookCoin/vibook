
Debian
====================
This directory contains files used to package vibookd/vibook-qt
for Debian-based Linux systems. If you compile vibookd/vibook-qt yourself, there are some useful files here.

## vibook: URI support ##


vibook-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install vibook-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your vibookqt binary to `/usr/bin`
and the `../../share/pixmaps/vibook128.png` to `/usr/share/pixmaps`

vibook-qt.protocol (KDE)

