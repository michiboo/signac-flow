.. _installation:

============
Installation
============

The recommendend installation method for **signac-flow** is via conda_ or pip_.
The software is tested for Python versions 3.4+ and only depends on the signac_ package.

.. _conda: https://anaconda.org/
.. _pip: https://docs.python.org/3.5/installing/index.html
.. _signac: https://glotzerlab.engin.umich.edu/signac

Install with conda
==================

To install **signac-flow** via conda, you first need to add the glotzer_ channel with:

.. _glotzer: https://anaconda.org/glotzer

.. code:: bash

    $ conda config --add channels glotzer

Once the **glotzer** channel has been enabled, **signac-flow** can be installed with:

.. code:: bash

    $ conda install signac-flow

All additional dependencies will be installed automatically.
To upgrade the package, execute:

.. code:: bash

    $ conda update signac-flow


Install with pip
================

To install the package with the package manager pip_, execute

.. code:: bash

    $ pip install signac-flow --user

.. note::
    It is highly recommended to install the package into the user space and not as superuser!

To upgrade the package, simply execute the same command with the ``--upgrade`` option.

.. code:: bash

    $ pip install signac-flow --user --upgrade


Source Code Installation
========================

Alternatively you can clone the `git repository <https://bitbucket.org/glotzer/signac-flow>`_ and execute the ``setup.py`` script to install the package.

.. code:: bash

  git clone https://bitbucket.org/glotzer/signac-flow.git
  cd signac-flow
  python setup.py install --user