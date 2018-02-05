==================================================================
DFO-LS: Derivative-Free Optimizer for Least-Squares |PyPI Version|
==================================================================
DFO-LS is a flexible package for solving nonlinear least-squares minimisation, without requiring derivatives of the objective.

This is an implementation of the algorithm from our paper: C. Cartis, J. Fiala, B. Marteau and L. Roberts, Improving the Flexibility and Robustness of Model-Based Derivative-Free Optimization Solvers, technical report, University of Oxford, (2018).

Documentation
-------------
See manual.pdf or `here <http://people.maths.ox.ac.uk/robertsl/dfols>`_.

Requirements
------------
DFO-LS requires the following software to be installed:

* Python 2.7 or Python 3 (http://www.python.org/)

Additionally, the following python packages should be installed (these will be installed automatically if using *pip*, see `Installation using pip`_):

* NumPy 1.11 or higher (http://www.numpy.org/)
* SciPy 0.18 or higher (http://www.scipy.org/)
* Pandas 0.17 or higher (http://pandas.pydata.org/)

Installation using pip
----------------------
For easy installation, use *pip* (http://www.pip-installer.org/) as root::

    $ [sudo] pip install dfols

or alternatively *easy_install*::

    $ [sudo] easy_install dfols

If you do not have root privileges or you want to install DFO-LS for your private use, you can use::

    $ pip install --user dfols

which will install DFO-LS in your home directory.

Note that if an older install of DFO-LS is present on your system you can use::

    $ [sudo] pip install --upgrade dfols

to upgrade DFO-LS to the latest version.

Manual installation
-------------------
Alternatively, you can download the source code from `Github <https://github.com/numericalalgorithmsgroup/dfols>`_ and unpack as follows:

 .. code-block:: bash

    $ git clone https://github.com/numericalalgorithmsgroup/dfols
    $ cd dfols

DFO-LS is written in pure Python and requires no compilation. It can be installed using:

 .. code-block:: bash

    $ [sudo] pip install .

If you do not have root privileges or you want to install DFO-LS for your private use, you can use:

 .. code-block:: bash

    $ pip install --user .

instead.

Testing
-------
If you installed DFO-LS manually, you can test your installation by running:

 .. code-block:: bash

    $ python setup.py test

Alternatively, the HTML documentation provides some simple examples of how to run DFO-LS.

Examples
--------
Examples of how to run DFO-LS are given in the `documentation <http://people.maths.ox.ac.uk/robertsl/dfols>`_, and the `examples <https://github.com/numericalalgorithmsgroup/dfols/examples>`_ directory in Github.

Uninstallation
--------------
If DFO-LS was installed using *pip* you can uninstall as follows:

 .. code-block:: bash

    $ [sudo] pip uninstall dfols

If DFO-LS was installed manually you have to remove the installed files by hand (located in your python site-packages directory).

Bugs
----
Please report any bugs using GitHub's issue tracker.

License
-------
This algorithm is released under the GNU GPL license.

.. |PyPI Version| image:: https://img.shields.io/pypi/v/DFOLS.svg
                  :target: https://pypi.python.org/pypi/DFOLS