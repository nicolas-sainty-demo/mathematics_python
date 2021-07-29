# mathematics_python

[![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)](https://forthebadge.com)\
[![forthebadge](https://forthebadge.com/images/badges/it-works-why.svg)](https://forthebadge.com)

INTRO
* The objective of this project is to solve a 4th degree equation: a4x
4 +a3x
3 +a2x
2 +a1x1 +a0 = 0. A direct
resolution method does exist (Ferrari’s method), but does not generalize to higher degrees. Thus, we will
rather compare 3 iterative algorithms:
* The bisection method,
* Newton’s method,
* The secant method.

USAGE
* ./105torus opt a0 a1 a2 a3 a4 n

DESCRIPTION
* opt method option:
  * 1 for the bisection method
  * 2 for Newton’s method
  * 3 for the secant method
* a[0-4] coefficients of the equation
* n precision (the application of the polynomial to the solution should
* be smaller than 10ˆ-n)
