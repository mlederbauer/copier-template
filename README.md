# copier-template

[Copier](https://github.com/copier-org/copier) template for pure Python libraries. Adapted from the copier template by the [LIAC](https://github.com/schwallergroup/copier-liac).

_As simple as possible. No magic._

Adapted from [copier-pylib](https://github.com/astrojuanlu/copier-pylib).

## Features

- [Hatch] for packaging.
- [pytest] for testing.
- [tox] for automation of test runners and other stuff.
- [Sphinx] for documentation
- [GitHub Actions] for continuous integration and publishing to PyPI.
- [mypy] for type checks.
- [ruff] for style checks and automatic Python code formatting.
- [pre-commit] for optional automation of style checks.

## Usage

Install `copier`:

```
pip install copier
```

Generate a Python package (make sure to create the directory of the project first):

```
copier copy gh:mlederbauer/copier-template path/to/destination
```

Create a new repository on github and run

```
git init
git remote add origin git@github.com:USERNAME/PROJECTNAME.git
git branch -M main
git add .
git commit -m "Initial commit"
git push -u origin main
```

## License

[MIT License](LICENSE)

[copier]: https://github.com/copier-org/copier/
[mypy]: http://mypy.readthedocs.io/
[Hatch]: https://hatch.pypa.io/
[pytest]: https://docs.pytest.org/
[Sphinx]: http://www.sphinx-doc.org/
[tox]: https://tox.readthedocs.io/
[ruff]: https://docs.astral.sh/ruff/
[pre-commit]: https://github.com/pre-commit/pre-commit/
[GitHub Actions]: https://github.com/features/actions/
