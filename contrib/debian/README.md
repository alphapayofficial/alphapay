
Debian
====================
This directory contains files used to package bitcoind/alphapay-qt
for Debian-based Linux systems. If you compile bitcoind/alphapay-qt yourself, there are some useful files here.

## bitcoin: URI support ##


alphapay-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install alphapay-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your alphapay-qt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoin128.png` to `/usr/share/pixmaps`

alphapay-qt.protocol (KDE)

