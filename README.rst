python-twitch |build-status| |coverage-status|
==============================================

python-twitch is an python module for simple interaction with twitch.

* `github version`_
* `pypi version`_

Installation
------------
``pip install python-twitch``

Usage
-----
Have a look at the tests_ directory.

You can supply your own Client-Id by overwriting ``twitch.CLIENT_ID``.

Development
-----------
To help with backwards compatibility tox_ environments are provided
that install all packages needed to run tests. Alternatively install
all development requirements via ``pip install -r dev_requirements``.

Credits
-------
This library was based on the `twitch.tv plugin for xbmc`_.

Changelog
---------
Since v0.4.0 changes are documented in the changelog_.


.. Links
.. _`pypi version`: https://pypi.python.org/pypi/python-twitch/
.. _`github version`: https://github.com/ingwinlu/python-twitch/
.. _`twitch.tv plugin for xbmc`: https://github.com/StateOfTheArt89/Twitch.tv-on-XBMC
.. _tests: https://github.com/ingwinlu/python-twitch/tree/master/tests
.. _tox: https://tox.readthedocs.org/en/latest/
.. |build-status| image:: https://img.shields.io/travis/ingwinlu/python-twitch/master.svg
   :target: https://travis-ci.org/ingwinlu/python-twitch
   :alt: Travis CI: continuous integration status
.. |coverage-status| image:: https://img.shields.io/coveralls/ingwinlu/python-twitch.svg
   :target: https://coveralls.io/r/ingwinlu/python-twitch
   :alt: Coveralls: code coverage status
.. _changelog: https://github.com/ingwinlu/python-twitch/blob/master/CHANGELOG.rst
