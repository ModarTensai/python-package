# Python Package

[![Last Commit](https://img.shields.io/github/last-commit/ModarTensai/python-package.svg)](https://github.com/ModarTensai/python-package/commits/master)
[![Repository Size](https://img.shields.io/github/repo-size/ModarTensai/python-package.svg)](https://github.com/ModarTensai/python-package/archive/master.zip)
[![Build Status](https://travis-ci.com/ModarTensai/python-package.svg?token=nsBux3TDRWWpFxuY8dgp&branch=master)](https://travis-ci.com/ModarTensai/python-package)
[![Total Downloads](https://img.shields.io/github/downloads/ModarTensai/python-package/total.svg)](https://github.com/ModarTensai/python-package/archive/master.zip)
[![License](https://img.shields.io/github/license/ModarTensai/python-package.svg)](https://github.com/ModarTensai/python-package/blob/master/LICENSE)


This is a minimal python package for a CLI app with automated unit tests and continuous integration bundled using [poetry](https://poetry.eustace.io/).

This project can take a lot of inspirations from [pendulum](https://github.com/sdispater/pendulum), which is made by the developer of poetry.

## Features

 - It has a [LICENSE](./LICENSE) file
 - It has a [README.md](./README.md) file
 - It is bundled using [poetry](https://poetry.eustace.io/)
 - [mkdocs](https://www.mkdocs.org/) documentation published using [GitHub pages](https://pages.github.com/) on a [custom domain](https://python-package.modar.me)
 - Shipped with a [VS Code](https://code.visualstudio.com/)'s workspace [file](./vs.code-workspace) and recommended [extensions](./.vscode/extensions.json)
    - Configured for python linting with [pep8](https://pypi.org/project/pep8/), [pylint](https://www.pylint.org/), [mypy](http://mypy-lang.org/) and [pydocstyle](http://www.pydocstyle.org/en/3.0.0/usage.html)
    - Enables auto-formating with Google style using [yapf](https://github.com/google/yapf) and [isort](https://pypi.org/project/isort/)
 - An example package of an English dictionary with the following:
    - Follows the guidelines specified by the mentioned linters
    - Type hints and annotations with [mypy](http://mypy-lang.org/)
    - Uses [pathlib](https://docs.python.org/3/library/pathlib.html), [logging](https://realpython.com/python-logging/) and [click](https://click.palletsprojects.com/en/7.x/)
    - Unit tested using [pytest](https://pytest.org) ([TODO] trying [pytest-mock](https://pypi.org/project/pytest-mock/))
 - Automated testing using [tox](https://tox.readthedocs.io/en/latest/) and stats using [pytest-cov](https://pytest-cov.readthedocs.io/en/latest/)
 - Continuous integration (CI) using [Travis-CI](https://travis-ci.com/) and GitHub badges using [shields](https://shields.io/)
 - [TODO] publish on [PyPI](https://pypi.org/) (and maybe [conda](https://conda.io))
 - [TODO] Makefile and VS Code tasks
 - [TODO] use [docker](https://www.docker.com/) and [kubernetes](https://kubernetes.io/)
 - [TODO] create a [cookiecutter](https://github.com/audreyr/cookiecutter)


## Requirements

The assumed operating system is Ubuntu and follow the [documentation](https://python-package.modar.me/requirements/):

 - [Install Python 3.7](https://python-package.modar.me/requirements/#installing-python-37-on-ubuntu-optional) (optional)
 - [Create a virtual environment](https://python-package.modar.me/requirements/#create-a-python-virtual-environment-on-ubuntu)
 - [Install JupyterLab](https://python-package.modar.me/requirements/#installing-jupyterlab-optional) (optional)
 - [Install Poetry](https://python-package.modar.me/requirements/#installing-poetry)

## Usage

We recommend using [VS Code](https://code.visualstudio.com/) and following the instructions provided [here](https://python-package.modar.me/usage/).

- [Documentation and GitHub Pages hosting](https://python-package.modar.me/usage/#documentation)
- [Command Line Interface (CLI)](https://python-package.modar.me/usage/#command-line-interface-cli)
- [Linting and testing](https://python-package.modar.me/usage/#linting-and-testing)

## License

[MIT](./LICENSE)

## Author

[Modar M. Alfadly](https://modar.me)

## Contributors

I would gladly accept any pull request to this repository.