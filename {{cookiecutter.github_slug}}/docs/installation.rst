.. highlight:: shell

============
Installation
============


Stable release
--------------

To install {{ cookiecutter.project_name }}, run this command in your terminal:

.. code-block:: shell

    $ pip install {{ cookiecutter.project_slug }}

This is the preferred method to install {{ cookiecutter.project_name }}, as it will always install the most recent stable release.

If you don't have `pip`_ installed, this `Python installation guide`_ can guide
you through the process.

.. _pip: https://pip.pypa.io
.. _Python installation guide: http://docs.python-guide.org/en/latest/starting/installation/


From sources
------------

This package is managed by the `PDM Python package manager <https://pdm-project.org/latest/>`_.
Once installed using pip (as shown below), PDM can be leaned on to run various scripts under the correct Python
virtual environment.

The sources for {{ cookiecutter.project_name }} can be downloaded from the `Github repo`_.

You can either clone the public repository:

.. code-block:: shell

    git clone git://github.com/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}

Or download the `tarball`_:

.. code-block:: shell

    curl -OJL https://github.com/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}/tarball/master

Then cd into the project root and run:

.. code-block:: shell

    pip install pdm
    pdm run install-dev

For a complete list of pre-configured PDM scripts provided with this package, run:

.. code-block:: shell

    pdm run --list

.. _Github repo: https://github.com/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}
.. _tarball: https://github.com/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}/tarball/master
