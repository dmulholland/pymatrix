
Pymatrix
========

A pure-Python matrix module with support for basic linear algebra operations.

Sample syntax:

    from pymatrix import matrix

    m = matrix([
        [1, 2],
        [3, 4]
    ])

    a = m + m * 2
    b = m * m
    c = m ** 3

    d = m.det()
    e = m.inverse()


Installation
------------

Install directly from the Python package index:

    $ pip install pymatrix


Requirements
------------

Tested with Python 2.7 and 3.4.


License
-------

This work has been placed in the public domain.
