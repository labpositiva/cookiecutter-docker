{{cookiecutter.project_name}}
==============================

{{cookiecutter.short_description}}

|Build Status| |Docker Stars| |Docker Pulls| |Code Climate| |GitHub stars| |Issue Count| |license| |Test Coverage|

:Version: {{cookiecutter.version}}
:Web: https://github.com/{{cookiecutter.github_user}}/{{cookiecutter.repo_name}}
:Download: https://github.com/{{cookiecutter.github_user}}/{{cookiecutter.repo_name}}
:Source: https://github.com/{{cookiecutter.github_user}}/{{cookiecutter.repo_name}}
:Keywords: {{cookiecutter.project_name}}

Download size of this image is only:

|MicroBadger|

.. contents:: Table of Contents:
    :local:

Requirements
------------

.. code-block:: bash

  make setup

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

Changelog
---------

Please see `CHANGELOG <CHANGELOG.md>`__ for more information what has
changed recently.

Contributing
------------

Please see `CONTRIBUTING <CONTRIBUTING.md>`__ for details.

Credits
-------

Made with :heart: :coffee: and :pizza: by `{{cookiecutter.company}} <https://github.com/{{cookiecutter.company}}>`__

-  `All Contributors <AUTHORS>`__

.. |Code Climate| image:: https://codeclimate.com/github/{{cookiecutter.github_user}}/{{cookiecutter.repo_name}}/badges/gpa.svg
   :target: https://codeclimate.com/github/{{cookiecutter.github_user}}/{{cookiecutter.repo_name}}
.. |GitHub issues| image:: https://img.shields.io/github/issues/{{cookiecutter.github_user}}/{{cookiecutter.repo_name}}.svg
   :target: https://github.com/{{cookiecutter.github_user}}/{{cookiecutter.repo_name}}/issues
.. |GitHub forks| image:: https://img.shields.io/github/forks/{{cookiecutter.github_user}}/{{cookiecutter.repo_name}}.svg
   :target: https://github.com/{{cookiecutter.github_user}}/{{cookiecutter.repo_name}}
.. |GitHub stars| image:: https://img.shields.io/github/stars/{{cookiecutter.github_user}}/{{cookiecutter.repo_name}}.svg
   :target: https://github.com/{{cookiecutter.github_user}}/{{cookiecutter.repo_name}}
.. |Issue Count| image:: https://codeclimate.com/github/{{cookiecutter.github_user}}/{{cookiecutter.repo_name}}/badges/issue_count.svg
   :target: https://codeclimate.com/github/{{cookiecutter.github_user}}/{{cookiecutter.repo_name}}
.. |license| image:: https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square
   :target: LICENSE
.. |Test Coverage| image:: https://codeclimate.com/github/{{cookiecutter.github_user}}/{{cookiecutter.repo_name}}/badges/coverage.svg
   :target: https://codeclimate.com/github/{{cookiecutter.github_user}}/{{cookiecutter.repo_name}}/coverage

.. |MicroBadger| image:: https://images.microbadger.com/badges/image/{{cookiecutter.github_user}}/{{cookiecutter.repo_name}}.svg
   :target: http://microbadger.com/images/{{cookiecutter.github_user}}/{{cookiecutter.repo_name}}
.. |Docker Stars| image:: https://img.shields.io/docker/stars/{{cookiecutter.github_user}}/{{cookiecutter.repo_name}}.svg?style=flat-square
   :target: https://hub.docker.com/r/{{cookiecutter.github_user}}/{{cookiecutter.repo_name}}
.. |Docker Pulls| image:: https://img.shields.io/docker/pulls/{{cookiecutter.github_user}}/{{cookiecutter.repo_name}}.svg?style=flat-square
   :target: https://hub.docker.com/r/{{cookiecutter.github_user}}/{{cookiecutter.repo_name}}

.. |Build Status| image:: https://travis-ci.org/{{cookiecutter.github_user}}/{{cookiecutter.repo_name}}.svg
   :target: https://travis-ci.org/{{cookiecutter.github_user}}/{{cookiecutter.repo_name}}