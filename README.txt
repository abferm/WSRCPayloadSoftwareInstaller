This package will install all the necessary packages to work on the Wichita State Rocket Club's scientific payload software.

A 32-bit Debian VM for VirtualBox is available for download at http://braindispenser.com/rocketVM.zip

To install:
1	add the following lines to /etc/apt/sources.list
deb http://braindispenser.com/htdocs/apt  sputnik main contrib non-free
deb-src http://braindispenser.com/htdocs/apt  sputnik main contrib non-free

2	run wget http://braindispenser.com/htdocs/apt/conf/repo.key && sudo apt-key add repo.key && sudo apt-get update && sudo apt-get install wsrc -y


Packages currently installed:
binutils
build-essential
dbus
make
cmake
avrdude
avr-libc
gdb-avr
gcc-avr
avrdude-doc
binutils-avr
nautilus-open-terminal
equivs
