# Docs-Bootstraper

Bootstrap project to quickly start working on any Docs project

## Always refer to latest Bootstraper for this readme.md

This readme.md file might be older. This file comes with a Bootstraper project. Once you clone the bootstraper project and copy it to your project, it becomes stale. This readme is only kept up-to-date on bootstraper project. Please refer back  there for its latest version

## Prerequisites

1. Python

2. Pip

## Upgrade to latest pip

```python
pip install --upgrade p
```

## Install mkdocs

```python
pip install mkdocs --user
pip install mkdocs-material --user
pip install mkdocs-material-extensions --user
```

## Create a new project on Github

Cretae a new project on Github and clone it.

## Clone Bootstrap Project

```bash
git clone git@github.com:andy-22/Docs-Bootstraper.git
```

## Copy project files from Bootstrap project

Copy File structure from Bootstrap project to a new project that you just made and cloned.

## Modify site settings

open site_settings.yml and change following variables:

1. site_name

2. repo_url: This is a repository url on github so that we can directly edit the page or section from the site itself

3. site_description

4. dev_addr: change port so that it doesn't interefere with other sites

## Build or Serve project

### Build

```python
python -m mkdocs build
```

### Serve (It will build as well as serve on http endpoint configured)

```python
python -m mkdocs serve
```

## Expected Results:

1. You should see a page with 404 and no errors on console except this page. Error is shown because we haven't populated `navs` in site_settings.yml.

2. Create any .md file in the `docs` directory and add to the `navs` in site_settings.yml and it will start showing up on the site.

## mkdocs material reference

In addition to markdown, we also can use mkdocs material special functionalities and its reference can be found here: [Reference - Material for MkDocs (squidfunk.github.io)](https://squidfunk.github.io/mkdocs-material/reference/)
