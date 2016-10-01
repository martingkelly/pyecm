# Pyecm
Pyecm factors large integers (up to 50 digits) using the Elliptic Curve Method
(ECM), a fast factoring algorithm.

Pyecm was a high-school project for myself (Martin Kelly) and my friend, Eric
Larson. Eric did more of the math and I did most of the code. Although the code
is not very clean by my standards today, it works and is quite fast. It was also
a nice illustration of how Python can be used for performance-critical code, if
the bottlenecks are clearly identified and implemented in C. In our case, we do
this via the wonderful gmpy.

# How to run pyecm

## All platforms
- First, make sure python (>= 2.3) is installed and working. You can always get
the latest release from http://python.org
- For speed increases, you may optionally install gmpy and/or psyco. Both are
highly recommended, especially gmpy, as they result in massive speed increases.

## Unix, Linux, Mac
- You can either use *python pyecm.py* to run it or change the filename to pyecm
and execute it as a script.

## Windows
- Just run pyecm.py as you would any other python program.

# Related projects
- Old home for pyecm on Sourceforge (https://sourceforge.net/projects/pyecm)
- gmpy (https://github.com/aleaxit/gmpy)
- psyco (http://psyco.sourceforge.net/)
