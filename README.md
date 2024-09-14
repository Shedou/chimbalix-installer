chimbalix-installer
============

Customizable GUI installer adapted for [Chimbalix](https://github.com/Shedou/Chimbalix).

Supports "portsoft" directory and other fixes.

### How To Build DEB Package:
Build-Depends: debhelper (>= 10) libzxcvbn-dev qtbase5-dev qttools5-dev-tools

Run in a terminal (inside the source folder):

fakeroot ./debian/rules binary

### Settings:
Check folder: /usr/share/chimbalix-installer/data

### Source Project (2024-09-14):

Adapted sources from MX Linux Repository:

https://mirror.truenetwork.ru/mxlinux/mx/repo/pool/main/g/gazelle-installer/gazelle-installer_24.05.01mx23.tar.xz

https://mirror.truenetwork.ru/mxlinux/mx/repo/pool/main/g/gazelle-installer-data/gazelle-installer-data_23.08mx23.tar.xz

Source project:
https://github.com/gazelle-installer/gazelle-installer
