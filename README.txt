This package will install all the necessary packages to work on the Wichita State Rocket Club's scientific payload software.

To install:
	add the following lines to /etc/apt/sources.list
deb http://braindispenser.com/htdocs/apt  sputnik main contrib non-free
deb-src http://braindispenser.com/htdocs/apt  sputnik main contrib non-free

	run sudo apt-get update && sudo apt-get install wsrc -y -y
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