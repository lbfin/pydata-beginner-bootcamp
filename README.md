## PyData London Beginners Bootcamp

Here you can find the 4 notebooks, as well as some pre-processing scripts and the datasets needed.

Included are html versions of the notebooks with output, and .ipynb versions without output.

All the notebooks are intended to be run with python3.6.

The files are also hosted [here](https://conrad.pythonanywhere.com/pydata/) and there is a tar file as well.


### Setup

    git clone https://github.com/conradho/pydata-beginner-bootcamp
    cd pydata-beginner-bootcamp
    mkvirtualenv pydata --python=`which python3.6`
    pip install -q -r requirements36.txt

To contribute to the repo:
1. `pip install nbstripout` then `nbstripout --install` from within your git repo. This will setup the git filters etc to strip out output from .ipynb files
2. use `jupyter-nbconvert --to html *.ipynb` to generate the corresponding html files

