You need to install [GeoClue2](http://www.freedesktop.org/wiki/Software/GeoClue/) on your machine before running the code.
On Arch it is available in AUR (geoclue2-git)

Then you can run `where-am-i.py`
It will print your location and exit after 10 seconds.

** Known issues - **

** Code runs but the location doesn't get printed **
- For this, run geoclue executable as root in another terminal. Location of the executable is in `org.freedesktop.GeoClue2.service` file
