================
AWS Data Toolkit
================


.. image:: https://img.shields.io/pypi/v/aws_data_toolkit.svg
        :target: https://pypi.python.org/pypi/aws_data_toolkit

.. image:: https://img.shields.io/travis/BenjaminDavison/aws_data_toolkit.svg
        :target: https://travis-ci.org/BenjaminDavison/aws_data_toolkit

.. image:: https://readthedocs.org/projects/aws-data-toolkit/badge/?version=latest
        :target: https://aws-data-toolkit.readthedocs.io/en/latest/?badge=latest
        :alt: Documentation Status


.. image:: https://pyup.io/repos/github/BenjaminDavison/aws_data_toolkit/shield.svg
     :target: https://pyup.io/repos/github/BenjaminDavison/aws_data_toolkit/
     :alt: Updates



Going all in on AWS for a modern data stack.


* Free software: MIT license
* Documentation: https://aws-data-toolkit.readthedocs.io.


Why?
----

AWS have a breadth of services to create a modern "serverless" data stack, but most examples
or frameworks are concentrated on one or two areas. This is also "my ideal stack" of low maintenance
infrastructure so you can concentrate on delivering value without being woken up at 3am
from a machine breaking. Let AWS handle as much of the boring stuff for you.

The project also contains support for (in my opinion) best of breed open source technology.

No Quicksight?
--------------

The only part of the stack that this project doesn't really address is BI tooling, as that's usually
in the analyst's domain. I'm just concentrating on getting them the data in a state that can be
queried by their tool of choice.

Features
--------

* Out of the box low maintenance data stack powered by AWS tools
* Data lake creation by AWS Lake Formation
* Data science by AWS Sagemaker
* Python ETL Handled by AWS Glue
* SQL ETL Handled by DBT
* Batch processing handled by AWS Batch
* Admin UI

Credits
-------

This package was created with Cookiecutter_ and the `audreyr/cookiecutter-pypackage`_ project template.

.. _Cookiecutter: https://github.com/audreyr/cookiecutter
.. _`audreyr/cookiecutter-pypackage`: https://github.com/audreyr/cookiecutter-pypackage
