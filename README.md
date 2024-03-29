# prognostics

[![Release](https://img.shields.io/github/v/release/valenparra/prognostics)](https://img.shields.io/github/v/release/valenparra/prognostics)
[![Build status](https://img.shields.io/github/actions/workflow/status/valenparra/prognostics/main.yml?branch=main)](https://github.com/valenparra/prognostics/actions/workflows/main.yml?query=branch%3Amain)
[![codecov](https://codecov.io/gh/valenparra/prognostics/branch/main/graph/badge.svg)](https://codecov.io/gh/valenparra/prognostics)
[![Commit activity](https://img.shields.io/github/commit-activity/m/valenparra/prognostics)](https://img.shields.io/github/commit-activity/m/valenparra/prognostics)
[![License](https://img.shields.io/github/license/valenparra/prognostics)](https://img.shields.io/github/license/valenparra/prognostics)

The objective of this project is to develop a robust prognostics model that predicts the remaining useful life (RUL) or failure probability of [specific system/asset] based on historical data and current condition monitoring. The aim is to enable proactive maintenance strategies, reduce downtime, and optimize resource allocation.

- **Github repository**: <https://github.com/valenparra/prognostics/>
- **Documentation** <https://valenparra.github.io/prognostics/>

## Getting started with your project

First, create a repository on GitHub with the same name as this project, and then run the following commands:

```bash
git init -b main
git add .
git commit -m "init commit"
git remote add origin git@github.com:valenparra/prognostics.git
git push -u origin main
```
**Comments on these commands:**

- `git init -b main`: Initializes a new Git repository with the main branch. The -b flag is used to specify the branch name. In this case, it's creating a main branch.
- `git add .`: Adds all files in the current directory to the staging area. The dot . represents all files.
- `git commit -m "init commit"`: Commits the changes added to the staging area with a message. In this case, the message is "init commit" indicating the initial commit.
- `git remote add origin git@github.com:valenparra/prognostics.git`: Adds a remote repository named 'origin' with the URL pointing to your GitHub repository. Replace valenparra/prognostics.git with your GitHub username and repository name.
- `git push -u origin main`: Pushes the committed changes to the 'main' branch of the remote repository (origin) and sets it as the upstream branch. This command effectively uploads your local changes to your GitHub repository.


```bash
make install
```

You are now ready to start development on your project!
The CI/CD pipeline will be triggered when you open a pull request, merge to main, or when you create a new release.

To finalize the set-up for publishing to PyPi or Artifactory, see [here](https://fpgmaas.github.io/cookiecutter-poetry/features/publishing/#set-up-for-pypi).
For activating the automatic documentation with MkDocs, see [here](https://fpgmaas.github.io/cookiecutter-poetry/features/mkdocs/#enabling-the-documentation-on-github).
To enable the code coverage reports, see [here](https://fpgmaas.github.io/cookiecutter-poetry/features/codecov/).

## Releasing a new version

- Create an API Token on [Pypi](https://pypi.org/).
- Add the API Token to your projects secrets with the name `PYPI_TOKEN` by visiting [this page](https://github.com/valenparra/prognostics/settings/secrets/actions/new).
- Create a [new release](https://github.com/valenparra/prognostics/releases/new) on Github.
- Create a new tag in the form `*.*.*`.

For more details, see [here](https://fpgmaas.github.io/cookiecutter-poetry/features/cicd/#how-to-trigger-a-release).

---

Repository initiated with [fpgmaas/cookiecutter-poetry](https://github.com/fpgmaas/cookiecutter-poetry).
