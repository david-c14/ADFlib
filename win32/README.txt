Microsoft Visual Studio solutions as an alternative to the linux toolchain.

VS2005 directory contains solutions and projects built against Visual Studio 2005
VS2012 directory contains solutions and projects built against Visual Studio 2012

For later versions of Visual Studio, you can probably allow visual studio to upgrade the solutions for you.


These solutions should not interfere with the linux toolchain build process.


Between versions 2003 and 2010 Microsoft Visual C++ was not C99 compliant!
The file win32/vs2005/stdint.h is supplied to fill the gap.
My thanks to Alexander Chemeris for making this file available



