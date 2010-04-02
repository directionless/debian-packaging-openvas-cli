These are my files for making a dpkg of openvas-cli.
It's a very trivial debian directory.

The control file can be regenerated with:

   ./debian/rules debian/control DEB_AUTO_UPDATE_DEBIAN_CONTROL=yes

but it probably won't need to be.

I made them for internal use at my employer, but others are welcome to them.
You probably want to change the maintainer email address
