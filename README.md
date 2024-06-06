<h1 align="center">📋 copier-poetry</h1>
<p align="center">
  <i><a href="https://github.com/copier-org/copier">Copier</a> template for <a href="https://github.com/python-poetry/poetry">poetry</a> projects.</i>
</p>


<!-- Place https://shields.io/ badges here -->
[![GitHub repo stars](https://img.shields.io/github/stars/worldworm/copier-poetry)](https://github.com/worldworm/copier-poetry)
[![License](https://img.shields.io/badge/license-MIT-green?logo=opensourceinitiative&logoColor=fff)](https://github.com/worldworm/copier-poetry/blob/main/LICENSE)
[![GitHub last commit (main)](https://img.shields.io/github/last-commit/worldworm/copier-poetry/main)](https://github.com/worldworm/copier-poetry/commits/main/)
[![GitHub release](https://img.shields.io/github/v/release/worldworm/copier-poetry)](https://github.com/worldworm/copier-poetry/releases/latest)
[![GitHub commits since latest release](https://img.shields.io/github/commits-since/worldworm/copier-poetry/latest/main)](https://github.com/worldworm/copier-poetry/releases/latest)
[![Copier supported version](https://img.shields.io/badge/Copier-v9-blue)](https://github.com/copier-org/copier)


## Features
- 📦 [Poetry](https://github.com/python-poetry/poetry) setup with a pre-defined pyproject.toml
- 🔁 Continuous integration (CI) pipelines for Github Actions and GitLab CI/CD
- 🐳 Docker support with build and publish pipelines
- ⚙️ Settings management using [pydantic-settings](https://github.com/pydantic/pydantic-settings)
- 🗄️ Database support with [sqlmodel](https://github.com/tiangolo/sqlmodel) and mysql, postgres or sqlite configuration
- ▶️ [alembic](https://github.com/sqlalchemy/alembic) database migrations
- 🏃 [poethepoet](https://github.com/nat-n/poethepoet) task runner
- 🪝 [pre-commit](https://github.com/pre-commit/pre-commit) hooks
- 🔍 [pylint](https://github.com/pylint-dev/pylint) code linter
- 🏁 [mypy](https://github.com/python/mypy) static type checker
- 🧪 [pytest](https://github.com/pytest-dev/pytest/) unit tests
- 🛡️ [bandit](https://github.com/PyCQA/bandit) code security check
- 🎨 [autopep8](https://github.com/hhatto/autopep8) and [pydocstringformatter](https://github.com/DanielNoord/pydocstringformatter) code formatter and styling
- 🆚 [VSCode](https://github.com/microsoft/vscode) configuration


## Requirements
First install copier:<br>
([from the official installation documentation](https://copier.readthedocs.io/en/stable/#installation))
```bash
pip install copier
```


## Usage

Make sure the requirements are met, then:
```bash
copier copy --trust "https://github.com/worldworm/copier-poetry.git" .
```

### Update
To update a template after creating a project, run:
```bash
copier update --trust -a .project/.copier-answers.poetry.yml .
```


## Explore more Copier templates
In addition to this template, there are a number of other Copier templates available. For an overview of all available templates, visit the [Templates Showcase repository](https://github.com/worldworm/copier-showcase).

---
<p align="center">
  <i>© <a href="https://github.com/worldworm">worldworm</a> 2023-2024</i>
  <br><i>Licensed under <a href="https://github.com/worldworm/copier-poetry/blob/main/LICENSE">MIT</a></i>
</p>
