# Python

A way to start a python project, preconfigured and with steps in a README.md file

This template is intended for use with macOS that has [homebrew](https://brew.sh) installed.

## Steps

1. Make sure poetry is installed on your system using homebrew.

```sh
brew install poetry # this will install poetry on your system
```

2. Clone this repository
3. Use poetry to initialize the virtual environment

```sh
poetry install # this will create a virtual environment and install the dependencies
```

4. Activate the virtual environment

```sh
poetry shell # this will activate the virtual environment
python --version # should be the version from the pyproject.toml file
exit # to deactivate the virtual environment
poetry env list # which environment is active
```

5. Add or remove new dependencies

```sh
poetry add <package-name> # to add a new dependency
poetry remove <package-name> # to remove a dependency
```
