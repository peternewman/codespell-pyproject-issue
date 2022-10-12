# codespell-pyproject-issue

There are typos in both `foo.py` and `ignored.txt`.

The codespell configuration is specified in `pyproject.toml` and the `tomli` dependency is installed.

`ignored.txt` is set to be ignore by the `skip = '*.txt,*.vtk'` line in the config.

Yet, codespell does not pick up on that because the feature isn't in a released version yet.
