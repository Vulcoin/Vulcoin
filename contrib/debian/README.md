
Debian
====================
This directory contains files used to package vuld/vul-qt
for Debian-based Linux systems. If you compile vuld/vul-qt yourself, there are some useful files here.

## vul: URI support ##


vul-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install vul-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your vulqt binary to `/usr/bin`
and the `../../share/pixmaps/vul128.png` to `/usr/share/pixmaps`

vul-qt.protocol (KDE)

