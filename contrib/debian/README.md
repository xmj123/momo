
Debian
====================
This directory contains files used to package momod/momo-qt
for Debian-based Linux systems. If you compile momod/momo-qt yourself, there are some useful files here.

## momo: URI support ##


momo-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install momo-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your momo-qt binary to `/usr/bin`
and the `../../share/pixmaps/desire128.png` to `/usr/share/pixmaps`

momo-qt.protocol (KDE)

