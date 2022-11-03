# Formatting

## Black
`python -m black {source_file_or_directory}`

## isort
`isort {source_file_or_directory}/**/*.py`

## mypy
`mypy {source_file_or_directory}`

# Testing
Run commands in the console in the project directory.

## pytest
`pytest`

## tox
`tox`

# Git Hooks

## Install hooks from config
`pre-commit install`

## Run against all files
Usualy performed when a new hook is added.
`pre-commit run --all-files`
