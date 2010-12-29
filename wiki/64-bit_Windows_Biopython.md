---
title: 64-bit Windows Biopython
permalink: wiki/64-bit_Windows_Biopython
layout: wiki
---

64-bit Windows Biopython
========================

64 Bit Windows machines normally use a 32 bit version of
Biopython/Python/NumPy. This page is a scratchpad documenting how to
generate a 64 bit version.

Firstly, such a version is already available, courtesy of Christoph
Gohlke at [Unofficial Windows Binaries for Python Extension
Packages](http://www.lfd.uci.edu/~gohlke/pythonlibs/).

To use a 64-bit version the following is needed: 64-bit Python and 64
bit NumPy. As of today, there is no official version 64 bit of NumPy.
Chris makes one available at the address above.

If you intend to compile Biopython from scratch then a **64 bit C
compiler is also needed**.

If you have both 32 bit and 64 bit versions of the above installed than
some care is needed to avoid mixups. Using the wrong compiler seems to
happen quite a bit (if you have both installed).

[mingw
64](http://sourceforge.net/projects/mingw-w64/files/Toolchains%20targetting%20Win64/Personal%20Builds/sezero_20101003/)