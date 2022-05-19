# Wine dependency fix for KDE Neon
Dummy package of libsane1:i386 for installing wine on KDE Neon.

# Usage
```
wget https://github.com/gnuhead-chieb/libsane1-i386-dummy/blob/main/libsane1_3.0_i386.deb?raw=true
apt install libsane1_3.0_i386.deb
```
after that,just install wine normally.You will be able to install wine without dependency problem!

# Building
```
equivs-build --arch i386 libsane1-dummy.ctl
```
