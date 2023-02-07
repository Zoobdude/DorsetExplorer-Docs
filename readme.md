# DorsetExplorer documentation project

This project contains the help documentation used in DorsetExplorer. The documentation is built using the [MkDocs Material](https://squidfunk.github.io/mkdocs-material/) static site generator.


## Pre-requisites

 - Python 3+ 
 - A text editor (we recommend Visual Studio Code) 
 - A terminal capable of running Python commands

## Installation

Follow the instructions at [Getting started - Material for MkDocs (squidfunk.github.io)](https://squidfunk.github.io/mkdocs-material/getting-started/) to install MkDocs on your machine.

## Editing and building the docs

The docs are written in [Markdown](https://commonmark.org/help/).
To add a new page, simply create a new file in the 'docs' folder with a .md extension and then add a reference to it in the 'nav' section of the mkdocs.yml file. It will appear in the same order in the yaml file and table of contents.
To see your changes as you edit them, open a terminal window in the root folder and run the following command.

`python -m mkdocs serve`

This will spin up a local server and hot reload as you make changes to the docs.
To build the documentation into a full static site ready for publishing, run the following command.

`python -m mkdocs build`

This will generate a folder in the root called 'site' with all the files you need.

## Publishing

TODO - Set up automated publishing 


## Further info

MkDocs Material documentaion - [Getting started - Material for MkDocs (squidfunk.github.io)](https://squidfunk.github.io/mkdocs-material/getting-started/)
