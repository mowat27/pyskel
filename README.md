# pyskel

Bare bones Python project creator

Makes a very simple python project.

Run `pyksel myproject` to create a `myproject` or just `pyskel` to be prompted for the name.

The project created has

* Basic `setup.py`
* `.gitignore` for Python and VSCode (from http://gitignore.io/api/python,visualstudiocode)
* Dependencies managed by pipenv
  - pytest 
  - autopep8
  - pylint
  - rope

`pyskel` initializes and git repo and commits everything too
