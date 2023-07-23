White: Black, but opposite
==========================

`Black <https://github.com/ambv/black>`_ is an amazing tool for auto–formatting
Python code in a style that I dislike. I use it in all my projects.

They made the wrong choice on strings, and it should be fixed

-----------

That is *exactly* what **white** does, it converts

::

    print(f"Hello {planet}")

to

::

    print(f'Hello {planet}')


It then invokes ``$ black -S --line-length 79`` on your behalf.



Usage
=====

::

    $ white myapp.py
    reformatted myapp.py
    

.. image:: http://share.kennethreitz.org/2L2m1U1A3m0L/Screen%20Shot%202018-03-15%20at%206.21.04%20AM.png


Installation
============

::

	$ pip install white

