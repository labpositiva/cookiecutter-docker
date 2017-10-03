Cookiecutter docker
===================

|Build Status| |GitHub issues| |GitHub license|

:Version: 0.1.0
:Web: https://github.com/labpositiva/cookiecutter-docker
:Download: https://github.com/labpositiva/cookiecutter-docker
:Source: https://github.com/labpositiva/cookiecutter-docker
:Keywords: Cookiecutter

Cookiecutter recipe to easily create docker project.

.. contents:: Table of Contents:
    :local:

Features
--------

-  Only Creates the necessary files and folders.
-  Blazing fast creation, forget about file creation and focus in
   actions.

Requirements
------------

.. code-block:: bash

   $ make setup

Actions Makefile
----------------

.. code-block:: bash

  λ make
      ༼ つ ◕_◕ ༽つ Makefile for Cookiecutter docker

      Usage:
          make environment               create environment with pyenv
          make install                   install dependences python by env
          make clean                     remove files of build
          make setup                     install requirements

          Docker:

              make docker.build         build all services with docker-compose
              make docker.down          down services docker-compose
              make docker.ssh           connect by ssh to container
              make docker.stop          stop services by env
              make docker.verify_network           verify network
              make docker.up             up services of docker-compose
              make docker.list           list services of docker

          Tests:

              test.lint                  Run all pre-commit
              test.syntax                Run all syntax in code

Usage
-----

.. code:: bash

  cookiecutter https://github.com/labpositiva/cookiecutter-docker.git

This will generate this folders (Please note the absence of templates
folder):

Changelog
---------

Please see `CHANGELOG <CHANGELOG.md>`__ for more information what has
changed recently.

Contributing
------------

Please see `CONTRIBUTING <CONTRIBUTING.md>`__ for details.

Credits
-------

Made with :heart: :coffee: and :pizza: by
`labpositiva <https://github.com/labpositiva>`__.

-  `All Contributors <AUTHORS>`__

.. |Build Status| image:: https://travis-ci.org/labpositiva/cookiecutter-docker.svg
   :target: https://travis-ci.org/labpositiva/cookiecutter-docker
.. |GitHub issues| image:: https://img.shields.io/github/issues/labpositiva/cookiecutter-docker.svg
   :target: https://github.com/labpositiva/cookiecutter-docker/issues
.. |GitHub license| image:: https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square
   :target: LICENSE
