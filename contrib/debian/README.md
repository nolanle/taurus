
Debian
====================
This directory contains files used to package taurusd/taurus-qt
for Debian-based Linux systems. If you compile taurusd/taurus-qt yourself, there are some useful files here.

## taurus: URI support ##


taurus-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install taurus-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your taurus-qt binary to `/usr/bin`
and the `../../share/pixmaps/taurus128.png` to `/usr/share/pixmaps`

taurus-qt.protocol (KDE)

