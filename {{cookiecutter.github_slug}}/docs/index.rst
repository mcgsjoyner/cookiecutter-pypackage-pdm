Welcome to {{ cookiecutter.project_name }}'s documentation!
{{ '=' * (11 + cookiecutter.project_name|length + 17) }}

.. toctree::
   :maxdepth: 2
   :caption: Contents:

   readme
   installation
   usage
   modules
   contributing
   {% if cookiecutter.create_author_file == 'y' -%}authors
   {% endif -%}history

Indices and tables
==================
* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
