Flatgui external for modern versions of Pure Data
=================================================

flatgui is a library of GUI objects which were part of the old 'flatspace' collection which was at some point discontinued.

Note on the restoration of this library
=======================================

Flatgui was written by various authors, and derived from a 2012-12-27k revision in pd-extended (externals/flatgui).

Although I am not the original author, I wish to maintain this library for backward compatibility with pd patches that cannot easily be switched from the traditional knob external in this repository to the excellent abcknob library in abctools, although I would still recommend abcknob highly.

As such, I wish to keep this library faithful to the older versions, but with compatiblity fixes for modern versions of PD, and portability fixes for FreeBSD, the latter of which I will soon contribute to numerous pd externals.

Also, if there were in the past any architecture portability issues in the past with amd64, they were overcome without changing anything.  I have been able to build and run flatgui with ease on FreeBSD 13-RELEASE amd64, and file indicates that these are 64-bit binaries.

Timothy Beyer 2022-04-09
