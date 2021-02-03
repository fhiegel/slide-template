# Sides Template

Static site template using MkDoc and RevealJS, in order to mix documentation and presentations.
Exemple available here: https://fhiegel.github.io/slide-template/

## Install

First, clone repository.

    git clone --recursive git@github.com:fhiegel/slide-template.git
    
If you forgot the "--recursive" part, don't worry and do the following

    git submodule update --init --recursive

## Install MKDoc and run your site

Install MkDocs and plugins, then run it

    pip install mkdocs mkdocs-material
    mkdocs serve

## Troubleshooting

When starting server locally, and going on slide page, you may encounter a Javascript error : the slide is blank.
To workaround, go in your submodule "revealjs" and format the file `theme/reveal.js/plugin/notes/notes.js`. 
