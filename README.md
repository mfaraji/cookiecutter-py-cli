# Python CLI Application Template

This is a [cookiecutter](https://github.com/cookiecutter/cookiecutter) template for generating
a Python command-line interface (CLI) application.

# Features

- [pytest](https://github.com/pytest-dev/pytest/) to run tests
- [click](https://github.com/pallets/click) to facilitate building a CLI application
(parsing and handling commands, arguments, options, etc.)
- `yml` file for [Travis](http://travis-ci.org/) CI
- Different choices of open source license

# Usage

- Install the requirements
```
pip install -r requirements.txt
```
- Generate project starting code
```
cookiecutter https://github.com/mfaraji/cookiecutter-py-cli
```
or
```
python -m cookiecutter https://github.com/mfaraji/cookiecutter-py-cli
```
