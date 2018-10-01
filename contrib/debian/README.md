
Debian
====================
This directory contains files used to package sandyd/sandy-qt
for Debian-based Linux systems. If you compile sandyd/sandy-qt yourself, there are some useful files here.

## sandy: URI support ##


sandy-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install sandy-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your sandyqt binary to `/usr/bin`
and the `../../share/pixmaps/sandy128.png` to `/usr/share/pixmaps`

sandy-qt.protocol (KDE)

