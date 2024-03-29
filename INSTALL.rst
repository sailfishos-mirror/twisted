Installing Twisted
==================

Installation Requirements
-------------------------

To install Twisted, you need:

- Python 3.8/3.9/3.10/3.11/3.12

- `setuptools <https://pypi.python.org/pypi/setuptools>`_
  (installed automatically if you use pip).

- `Zope Interface <https://pypi.python.org/pypi/zope.interface>`_  4.4.2 or newer.
  Installing via pip will automatically download a suitable Zope Interface.

- On Windows `pywin32 <https://pypi.python.org/pypi/pywin32>`_ is required.
  Build 223 or later is highly recommended for reliable operation.

We also have `setuptools extras <http://twistedmatrix.com/documents/current/installation/howto/optional.html>`_ for automatically installing optional packages used by Twisted.


Installing Twisted
------------------

To install the latest version of Twisted using pip::

  $ pip install twisted

You can install optional dependencies for specific functionality in Twisted (such as TLS or serial support) by using our setuptools extras (see above).

As an example, to install Twisted with the TLS dependencies, use::

  $ pip install twisted[tls]
