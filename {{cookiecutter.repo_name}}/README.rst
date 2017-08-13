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
    \{^_^}/ Commands
      build                Build docker container by env
      clean                clean Files compiled
      documentation        Make Documentation
      down                 remove containers docker by env
      environment          Make environment for developer
      env                  Show envs available
      install              Install with var env Dependences
      list                 List of current active services by env
      lint                 Clean files unnecesary
      test                 make test
      up                   Up application by env
      restart              Reload services
      ssh                  Connect to container
      stop                 stop containers docker by env
      setup                Install dependences initial
      verify_network       Verify network
      help                 Show help text


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