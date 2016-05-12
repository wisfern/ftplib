# ftplib
a ftplib of C++, version 4, http://nbpfaus.net/~pfau/ftplib/

# 4.0-1
FTP Library Routines Release 4.0
Thomas Pfau (tfpfau@gmail.com)
March 9, 2016

This package implements a callable interface to FTP.  The FTP protocol is
specified in RFC 959.  The library has been tested on linux, OpenVMS and
Windows NT.  It should also work without major modification on other
POSIX systems.

All programs using the library should include ftplib.h.

The routines look at the global variable ftplib_debug to determine how
much information they should display.  Level 1 has been left for user
programs.  Level 2 displays all responses received from the server.
Level 3 displays all commands sent to the server.

Function documentation is provided in HTML format in the html
subdirectory.

