libircclient v1.6.0
============

libircclient is a small but extremely powerful library which implements the IRC protocol. It is designed to be small, fast, portable and compatible with the RFC standards as well as non-standard but popular features. It is perfect for building the IRC clients and bots.
This was forked from the CVS stable repository on sourceforge: http://sourceforge.net/projects/libircclient/

### Building from sources 

The library uses autoconf so it is build in a fairly typical way on most Unix systems:
<pre>
./configure
make
</pre>
This will build both the library and various examples in the examples subdirectory.

Configure script also accepts parameters, optional useful parameters accepted are –-enable-openssl and –-enable-ipv6 which correspondingly enable the SSL and IPv6 connectivity. Use –-enable-shared to build a shared library.

The same procedure is used to build the Win32 binary using the MinGW compiler.

For the rest see the Doxygen documentation in the header files and http://www.ulduzsoft.com/libircclient/

### License

LGPL: http://www.gnu.org/licenses/lgpl.txt



