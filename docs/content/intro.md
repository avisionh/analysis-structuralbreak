# Introduction

Welcome to the start of your journey into analysing time-series data within Python.

The focus of this book is to enable you to get started as soon as possible with analysing,
modelling and forecasting time-series data.

***

## The Platform: Jupyter Book

Jupyter Book lets you build an online book using a collection of Jupyter Notebooks
and Markdown files. Its output is similar to the excellent [Bookdown](https://bookdown.org/yihui/bookdown/) tool,
and adds extra functionality for people running a Jupyter stack.

For an example of a book built with Jupyter Book, see the [textbook for Data 100](https://www.textbook.ds100.org/) at UC Berkeley.

Here are a few features of Jupyter Book

* All course content is written in markdown and Jupyter Notebooks, stored in `notebooks/`
* The Jupyter Book repo comes packaged with helper scripts to convert these into Jekyll pages (in `scripts/`) that can be hosted for free on GitHub
* Pages can have [Binder](https://mybinder.org) or JupyterHub links automatically added for interactivity.
* The website itself is based on Jekyll, and is highly extensible and can be freely-hosted on GitHub.
* There are lots of nifty HTML features under-the-hood, such as Turbolinks fast-navigation and
  click-to-copy in code cells.

### Getting started

To get started, you may be interested in the following links.
Here are a few links of interest:

* **[Quickstart](features/features)** is a quick demo and overview of Jupyter Book.

* **[The Jupyter Book Guide](guide/01_overview)**
  will step you through the process of configuring and building your own Jupyter Book.

* **[The Jupyter Book template repo](https://github.com/jupyter/jupyter-book)** is the template
  repository you'll use as a start for your Jupyter Book.

* **A demo of the Jupyter Book** can be browsed via the sidebar to the left.

### Installation

Here's a brief rundown of how to create your own Jupyter Book using this site. For a more
complete guide, see [the Jupyter Book guide](guide/01_overview).

* Fork the Jupyter Book template repo
* Replace the demo notebooks in `content/` with your own notebooks and markdown files.
* Create a Table of Contents yaml file by editing `_data/toc.yaml`.
* Generate the Jekyll markdown for your notebooks by running `scripts/generate_book.py`
* Push your changes to GitHub (or wherever you host your site)!

***

## Acknowledgements
Before we proceed further, enormous debt is owed to Rob Hyndman's and George Athanasopoulos'
excellent ebook [Forecasting: Principles and Practice](https://otexts.com/fpp2/) for which
this book owes plenty to.

Also, a huge thanks to [Alessia Tosi][atosi] for her expert judgement and guidance throughout.

[atosi]: https://github.com/exfalsoquodlibet

Jupyter Book was originally created by [Sam Lau][sam] and [Chris Holdgraf][chris]
with support of the **UC Berkeley Data Science Education Program and the Berkeley
Institute for Data Science**.

[sam]: http://www.samlau.me/
[chris]: https://predictablynoisy.com
