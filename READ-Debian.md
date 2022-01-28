Debian
This directory contains files used to package KiTeeCoind/KiTeeCoin-qt for Debian-based Linux systems. If you compile KiTeeCoind/KiTeeCoin-qt yourself, there are some useful files 
here.

KiTeeCoin: URI support
KiTeeCoin-qt.desktop (Gnome / Open Desktop) To install:

sudo desktop-file-install KiTeeCoin-qt.desktop
sudo update-desktop-database
If you build yourself, you will either need to modify the paths in the .desktop file or copy or symlink your KiTeeCoin-qt binary to /usr/bin and the ../../share/pixmaps/KiTeeCoin128.png 
to /usr/share/pixmaps

KiTeeCoin-qt.protocol (KDE)
