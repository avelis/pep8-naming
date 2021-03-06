Changes
=======

0.5.0 - 2018-01-02
------------------

* Add configurable list of classmethod and staticmethod decorators

* Print the offending name as part of the error message

* Correct N804/N805 for __init_subclass__


0.4.1 - 2016-06-26
------------------

* Note to self: Never do releases before ~0600 or coffee on a Sunday.

* Fix option parsing for Flake8 3.0 (store parsed value on class)


0.4.0 - 2016-06-26
------------------

* Fix integration with Flake8 3.0.0b1

* Start testing against Python 3.5


0.3.3 - 2015-06-30
------------------

* Fix bug where ignored names were not properly split into a list.


0.3.2 - 2015-06-14
------------------

* Fix bug trying to call ``split`` on a list.


0.3.1 - 2015-06-14
------------------

* Fix optparse exception resulting from trying to register an option twice.


0.3.0 - 2015-06-14
------------------

* Relaxed N806 checking for use with namedtuples

* Add ``--ignore-names`` which allows the user to specify a list of names to
  ignore. By default this includes ``setUp``, ``tearDown``, ``setUpClass``,
  and ``tearDownClass``.


0.2.2 - 2014-04-19
------------------

* Do not require ``setuptools`` in setup.py.  It works around an issue
  with ``pip`` and Python 3.

* ``__new__`` is now considered as ``classmethod`` implicitly

* Run unit tests on travis-ci.org for python2.6, 2.7, 3.2, and 3.3

* Add unit tests and support running them with setup.py

* Support Python 3.4 


0.2.1 - 2013-02-22
------------------
* Do not require ``flake8``


0.2 - 2013-02-22
----------------

* Rename project ``flint-naming`` to ``pep8-naming``

* Fix a crash when function argument is a tuple of tuples


0.1 - 2013-02-11
----------------

* First release
