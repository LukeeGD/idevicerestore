# idevicerestore

This tool allows to restore firmware files to iOS devices.

It is a full reimplementation of all granular steps which are performed during restore of a firmware to a device. 

In general, upgrades and downgrades are possible, however subject to availability of SHSH blobs from Apple for signing the firmware files. This version created for using Odysseus method for 32-bit devices. 

To restore a device to some firmware, simply run the following:
$ idevicerestore -w

## Requirements
### Development Packages of:
      libcurl
	libimobiledevice
	libirecovery
	libusbmuxd
	libplist
	libzip
      zlib
	openssl

### Software:
	make
	autoheader
	automake
	autoconf
	libtool
	pkg-config
	gcc

## Installation
To compile run:

	./autogen.sh && make && sudo make install

## Who/What/Where?

Home:
	http://www.libimobiledevice.org/

Original code:
	git clone http://git.libimobiledevice.org/idevicerestore.git

This fork code:
        git clone https://github.com/s0uthwest/idevicerestore.git

Tickets:
	http://github.com/libimobiledevice/idevicerestore/issues

Mailing List:
	http://lists.libimobiledevice.org/mailman/listinfo/libimobiledevice-devel

IRC:
	irc://irc.freenode.net#libimobiledevice

## Credits

Apple, iPhone, iPod, and iPod touch are trademarks of Apple Inc.
idevicerestore is an independent software tool and has not been authorized, sponsored, or otherwise approved by Apple Inc.

README Updated on:

	2019-06-25
