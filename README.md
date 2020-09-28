# SunPy Sphinx Theme

[![PyPI version](https://badge.fury.io/py/sunpy-sphinx-theme.svg)](https://badge.fury.io/py/sunpy-sphinx-theme)
[![Build Status](https://travis-ci.org/sunpy/sunpy-sphinx-theme.svg?branch=master)](https://travis-ci.org/sunpy/sunpy-sphinx-theme)

This repository contains the still work in progress sphinx theme for the new website and documentation.

To use put this in your `conf.py` file:

    from sunpy_sphinx_theme.conf import *

## Dropdown

If you want to add entries to the dropdown menus you can find them in `sunpy_sphinx_theme/conf.py`.

## Sidebar

We do not have a recursive check for the sidebar on all pages.

If you want to add pages to the sidebar you can find ``html_sidebars`` in `sunpy_sphinx_theme/conf.py`.

You will want to add to this in your own packages ``conf.py``
