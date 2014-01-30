Ectroverse 2.0!
========
Ectroverse 2.0 is a recode of a recode!
This version is using the NEctroverse source as a base.


To install the game:<br>
Edit config/buildflags.h to ajust optinal addins.<br>
Edit config/evconfig.ini and change as required.<br>

If an invalid config is found, you will recive a shell notice.<br>
If no file exists, the game will create a blank template for your ajustment.

Additional Librarys needed for components:
* build-essential -- needed, but you should already have that.
* libpng-dev -- needed to render the galaxy map.
--Below are Optional's
* libmysqlclient-dev -- needed for mySql addition.
* libgnutls-dev -- For HTTPs support.
* libcurl4-gnutls-dev -- For Facebook support.

Run:
* make 
* ./evserver

That's it...<br>
Map creation is embeded into the core.

KNOWN BUGS - Very annoying and need to go:
* Facebook linkage is unstable.
* ... Possibly more
* ... Join and help find them all!
* .... ?
