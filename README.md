# pyproject-templates
Cookiecutter templates to start projects with `pyproject.toml`.

Useful links

- [packaging-projects](https://packaging.python.org/en/latest/tutorials/packaging-projects/).
- [hatch](https://hatch.pypa.io/latest/)

Generating distribution archive:

```
pip install --upgrade build

python -m build
```

## Examples

```
cookiecutter plain-template-stubs --no-input project_name=crodi project_description="Stubs files for c-rodi"
```
