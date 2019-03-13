# pdnsd with some extras

Added features:
* systemd sd-notify support
* add Upstart job file
* add Systemd Service unit file
  * with lot of hardening options
* raise debian/compat level from 9 to 11

Based on upstream 1.9.2a-par2.
Debian source folder comes from Ubuntu Trusty.

Tested on Ubuntu Bionic 18.04 as well.

Pre-generated 'configure' file has been removed. Please run 'autoconf' at the beginning of the compile process.

If you would like build deb package:

    dpkg-buildpackage -b -uc -rfakeroot

You can find more documentations in README and README.par files.
