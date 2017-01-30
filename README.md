# Jupyter Notebooks at Research Bazaar

This tutorial covers Jupyter and IPython [at Research Bazaar](http://www.ub.uio.no/english/courses-events/courses/other/Carpentry/software-carpentry/time-and-place/170202_jupyter).

## Goals

Jupyter and IPython are tools that can help you get your programming work done and communicate your computational ideas. Learn how notebooks can fit into your work, and help you get your research done and out into the world.

You will learn

- how to install Jupyter and start Jupyter notebooks
- how to combine text, executable code and graphics (figures) in the notebook
- how to share your notebook with colleagues or the world
- how to find and use interesting notebooks shared by others

Audience: novice programmers with interest in computational research, especially with some experience in the Python programming language.

## Setup

In its current form, this tutorial is meant to be executed with Jupyter Notebook 4.3 or
newer.  You can find our installation instructions [here](https://jupyter.org/install.html).

If you prefer using pip, you can also run:

	pip install --upgrade notebook

which should give you all the necessary dependencies.


To get the tutorial, checkout the `resbaz-2017` repo:

    git clone https://github.com/minrk/resbaz-2017

Or just
[download current master](https://github.com/minrk/resbaz-2017/zipball/master)
and unzip it.

At the command line, you can do this with (depending on whether your system
uses wget or curl):

    wget https://github.com/minrk/resbaz-2017/zipball/master -O resbaz-2017.zip

or

    curl -L https://github.com/minrk/resbaz-2017/zipball/master -o resbaz-2017.zip

and then:

	unzip resbaz-2017.zip

You can then start the  notebook server at a terminal with:

    jupyter notebook
