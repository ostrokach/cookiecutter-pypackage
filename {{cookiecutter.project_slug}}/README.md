{% set is_open_source = cookiecutter.open_source_license != 'Not open source' -%}
# {{ cookiecutter.project_name }}

{% if is_open_source %}
[![conda](https://img.shields.io/conda/dn/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}.svg)](https://anaconda.org/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}/)
[![docs](https://img.shields.io/badge/docs-v{{ cookiecutter.version }}-blue.svg)](https://{{ cookiecutter.github_username }}.gitlab.io/{{ cookiecutter.project_slug }}/)
{%- endif %}
[![build status](https://gitlab.com/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}/badges/master/build.svg)](https://gitlab.com/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}/commits/master/)
[![coverage report](https://gitlab.com/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}/badges/master/coverage.svg)](https://gitlab.com/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}/commits/master/)

{{ cookiecutter.project_short_description }}

## Features

* TODO
