# Introduction to python at the University of York
A small collection of guided introductions to python for students studying Computational Plasma Physics at the University of York

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/d7919/introduction_to_python_at_york/main)

## What is this for?

These resources are not intended to provide a complete introduction to
all aspects of programming in python, rather they are supposed to
introduce some of the key concepts/approaches that we will be using
through several modules. Broadly speaking, by reviewing these
resources and practicing some of the concepts introduced it is hoped
that one will be able to read in some data from file, fit a curve to
this and to produce a well presented plot showing the raw data and the
fit.

## Using these resources

### Binder

One can interact with the exercises through your browser and without
installing any additional software. Click the "launch | binder" badge
in the readme or click this link to [open in
binder](https://mybinder.org/v2/gh/d7919/introduction_to_python_at_york/main). This
is a web based service which offers the ability to work with python
through Jupyter notebooks in your browser.

### Run locally

If you'd rather work locally / offline at a later date then one can follow these steps from a suitable terminal:

~~~
# Clone the repository
git clone https://github.com/d7919/introduction_to_python_at_york.git

# Change directory
cd introduction_to_python_at_york

# Create a python virtual environment, activate it and install dependencies
python -m venv intro
source intro/bin/activate
pip install -r requirements.txt
~~~

The previous steps should be a one-off setup. To launch the exercises you can do the following from the `introduction_to_python_at_york` directory:

~~~
source intro/bin/activate
jupyter lab
~~~

Finally, when you're done you probably want to run `source intro/bin/deactivate`.
