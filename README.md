# IntelligentAppFactory
Public repository to detail how intelligent app can be secured, developed, and architected at scale.


# Running locally on windows

[Install Python 3.11.6](https://www.python.org/downloads/release/python-3116/)

```
python --version
```

## Virtual Env

https://docs.python.org/3/tutorial/venv.html

Run

```
python -m venv venv
```

Run

```
venv\Scripts\activate
```

install/ upgrade pip

```
python -m pip install --upgrade pip
```

Install packages

```
pip install -r .\requirements.txt
```

To deactivate virtual environment `deactivate`

More info: https://docs.python.org/3/tutorial/venv.html

# MK Docs

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

[mkdocs-material documentation](https://squidfunk.github.io/mkdocs-material/reference/)

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.