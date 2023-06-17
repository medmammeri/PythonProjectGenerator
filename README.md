
Python package generator

## Usage

## Features

- Package management with [Poetry](https://python-poetry.org/).
- Ready-to-use Makefile for common development tasks.
- Continuous Integration (CI) pipeline with GitHub Actions for tests and lints.
- GitHub Actions workflow for building and deploying documentation using [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/).

### Package Management with Poetry

The project uses [Poetry](https://python-poetry.org/) for package management. You can manage different dependency groups by using the following commands:

- `poetry install` - Installs all project dependencies.
- `poetry add package-name` - Adds a new package as a project dependency.
- `poetry add --dev package-name` - Adds a development-specific package as a project dependency.
- `poetry remove package-name` - Removes a package from the project dependencies.

Make sure to update the `pyproject.toml` file to define your package dependencies and groups accordingly.

### Makefile

The project includes a ready-to-use Makefile that provides useful commands for development and automation. Some of the available commands are:

- `make lint` - Runs linting checks using [flake8](https://flake8.pycqa.org/).
- `make test` - Runs tests using [pytest](https://pytest.org/).
- `make docs` - Generates documentation using [MkDocs](https://www.mkdocs.org/).

Refer to the Makefile for more details and additional commands that may be available.

### Continuous Integration with GitHub Actions

The project utilizes GitHub Actions to set up a continuous integration (CI) pipeline. The CI pipeline performs automated tests and linting. You can find the workflow configuration in `.github/workflows/ci.yml`.

### GitHub Pages Documentation

The generated project is configured to build and deploy documentation using [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/). The documentation is automatically built and deployed to GitHub Pages. You can access the documentation at [your-username.github.io/your-repository](https://your-username.github.io/your-repository/).



## Project Structure

