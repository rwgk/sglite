SgLite (c) 1994-2000 Ralf W. Grosse-Kunstleve

SgLite is based on SgInfo and formed the foundation for cctbx/sgtbx.
It was used in PyMOL from 2000 to 2008.
The PyMOL development history was reconstructed under
https://github.com/rwgk/sglite (use git log to inspect).

All code except sglitemodule.c and runtests.c compiles without warnings
with gcc or clang -Wall.

sglitemodule.c was written for Python 1.5.2 and stopped working with
Python 2.2. It's kept here only for reference.

See also:
https://github.com/rwgk/sginfo  # Known bugs but documented (incl. known bugs).
http://cctbx.sf.net/  # Look for sgtbx.
