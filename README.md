# Sides Template

Static site template using MkDoc and RevealJS, in order to mix documentation and presentations.

## Install

First, clone repository.

    git clone --recursive git@github.com:fhiegel/slide-template.git
    
If you forgot the "--recursive" part, don't worry and do the following

    git submodule update --init --recursive

## Install MKDoc and run your site

Install MkDocs and plugins, then run it

    pip install mkdocs mkdocs-material
    mkdocs serve
