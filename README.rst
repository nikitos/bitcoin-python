bitcoin-python is a set of Python libraries that allows easy access to the
bitcoin peer-to-peer cryptocurrency client API.


Documentation
===========================

Documentation can be found here, or in the source archive. It is built
using Sphinx:

http://laanwj.github.com/bitcoin-python/doc/

Installation instructions
===========================

bitcoin-python uses setuptools for the install script. There are no dependencies apart from Python itself.

::

  $ python setup.py build
  $ python setup.py install

Pypi / Cheeseshop
==================

It is possible to install the package through Pypi (cheeseshop), see http://pypi.python.org/pypi?:action=display&name=bitcoin-python

::

  $ pip install bitcoin-python

TODO
======
These things still have to be added:

- SSL support (including certificate verification) for managing remote bitcoin daemons.

