# Brown Graduate AI Luncheon talks

Website: https://brown-graduate-ai-luncheon.github.io

## How to compile the website:

This website uses `jinja2` to convert `index.template.html` into `index.html` using data in `static/data`.
If you're missing `jinja2`, you'll need to install it first.

Run: `python3 compile.py`
or, simply: `make` to use the Makefile included.

## How to update content:

Information about upcoming talks lives in the YAML file at `static/data/talks.yml`. Additional information about venues and organizers lives both, in the templated html and at `static/data/info.yml`. Make sure to run `compile.py` after any edits. Then, check `index.html` to make sure the changes look right, and commit and push the file.

## Credits

Adapted by Etha. Made by Mikey Lepori and Aalok Sathe. Website skeleton adapted from [Nerfies](https://nerfies.github.io/).
