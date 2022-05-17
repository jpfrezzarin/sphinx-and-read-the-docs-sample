# Sphinx & Read the Docs Sample

A sample of a project with sphinx for documentation, integrated with Read the Docs

[Click here](https://sphinx-and-read-the-docs-sample.readthedocs.io/en/latest/) to see the documentation of this repository in the Read the Docs site. 

## Stack

- Python (3.10.4)

## Restore

To restore dependencies, run the command bellow in project path:

```
pip install -r docs/requirements.txt
```

## Build

To build the html files locally, run the command bellow inside `docs` path:

```
make html
```

For windows user, run:

```
.\make.bat html
```