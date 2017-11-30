# Installation

## Stable release

To install {{ cookiecutter.project_name }}, run this command in your terminal:

```bash
conda install {{ cookiecutter.project_slug }} -c {{ cookiecutter.github_username }}
```

This is the preferred method to install {{ cookiecutter.project_name }}, as it will always install the most recent stable release.

If you don't have [conda] installed, this [Python installation guide] can guide
you through the process.

[conda]: https://conda.io
[Python installation guide]: https://conda.io/docs/user-guide/install/index.html

## From sources

The sources for {{ cookiecutter.project_name }} can be downloaded from the [GitLab repo].

You can either clone the public repository:

```bash
git clone git://gitlab.com/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}
```

Or download the [tarball]:

```bash
curl -OL https://gitlab.com/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}/tarball/master
```

Once you have a copy of the source, you can install it with:

```bash
python setup.py install
```

[GitLab repo]: https://gitlab.com/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}
[tarball]: https://gitlab.com/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}/tarball/master
