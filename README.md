# sphinx-template

Sphinx can be used to create general documentation, not just for Python modules.
It supports reStructuredText (reST) and Markdown, making it a versatile tool for documentation.

This repo is a playground / reference for creating documentation with Sphinx.

## Download dependencies

### Install `pandoc` for `.md` to `.rst` file conversion

Install `pandoc` via Homebrew if you haven't done so already:

```bash
brew install pandoc
```

### Install other dependencies

```bash
pip3 install -r requirements.txt
```

## Optional: Initialize Sphinx Project

If a Sphinx project hasn't been initialized, run the command:

```bash
sphinx-quickstart
```

## Build documentation

```bash
sphinx-build -b html . _build
```

## Clean the build directory and re-build

```bash
make clean
sphinx-build -b html . _build
```

## View built documentation

Open the `index.html` file located in the `_build` directory.
