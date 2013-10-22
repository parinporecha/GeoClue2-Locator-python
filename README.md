You need to install [GeoClue2](http://www.freedesktop.org/wiki/Software/GeoClue/) on your machine before running the code.
- [This page](http://pkgs.org/search/?keyword=geoclue2) contains the links to download GeoClue2 for Arch, Fedora, OpenSuse and AltLinux
- For Debian based systems, [this page](http://packages.debian.org/experimental/geoclue) has the .deb package

Then you can run `where-am-i.py`
It will print your location and exit after 10 seconds.

**Known issues -**

**Code runs but the location doesn't get printed**
- For this, run geoclue executable as root in another terminal. Location of the executable is in `org.freedesktop.GeoClue2.service` file
