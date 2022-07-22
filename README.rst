Status
------

**This project is unmaintained**. It was originally spun off of
django-auth-ldap, which no longer requires it. If you have a use for it, feel
free to copy the code for your own purposes (it's only for testing, after all).

Documentation may still be available at https://mockldap.readthedocs.io/.

------

ELIXIR Luxembourg note::

This repository has been forked because the original *mockldap* package that is on pypi is greatly outdated, and requires packages that just don't work with modern Python.
If a python project used to depend on _mockldap_, you can replace the entry in requirements.txt or setup.py with: ``'mockldap@git+https://github.com/elixir-luxembourg/mockldap2.git'``