Flatgui external for modern versions of Pure Data
=================================================

Flatgui is a library of GUI objects which were part of the old 'flatspace' collection which was at some point discontinued.

# Note on the restoration of this library

Flatgui was written by various authors, and this repository was derived from a 2012-12-27 revision in pd-extended (externals/flatgui).

Based on the project metadata, this library was originally written by Ben Bogart, Christoph Kummerer, Frank Barknect, Guenther Geiger, Hans-Christoph Steiner, Krzystof Czaja, Miller Puckette, Olaf Matthes and Thomas Musil.

Although I am not the original author, I wish to maintain this library for backwards compatibility with PD patches that cannot easily be switched from the traditional knob external (in this repository) to the excellent abcknob library in abctools, although I would still recommend abcknob highly.

As such, I wish to keep this library faithful to older versions, but with compatibility fixes for modern versions of PD, and portability fixes for FreeBSD, the latter of which I will soon contribute to numerous PD externals.

Also, if there were in the past any architecture portability issues in the past with amd64, they were overcome without changing anything.  I have been able to build and run flatgui with ease on FreeBSD 13-RELEASE amd64, and the file command indicates that these are 64-bit binaries.

Timothy Beyer 2022-04-09
