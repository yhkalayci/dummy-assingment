# Dummy Assignment

### Jupyter and Octave Kernel Installation

This assignment is intended to illustrate [workflow](https://github.com/CMPE482-Spring2017-Bogazici/course-description/blob/master/README.md) for assignment and project submission. In order to use Jupyter notebooks, you should install python first. We recommend unexperienced users to install [miniconda](https://conda.io/miniconda.html) or [anaconda](https://www.continuum.io/downloads), these distributions will handle most of the tedious job.

To install Jupyter by using [conda](https://conda.io/docs/using/pkgs.html#install-a-package) use `conda install jupyter` command (if you installed miniconda, because anaconda automatically installs Jupyter).

To install [Octave kernel](https://github.com/Calysto/octave_kernel) to Jupyter you need to have [Octave](https://www.gnu.org/software/octave/) installed (as you might guess) and the path of its executable should be appended to `PATH` variable. Then you can install kernel as follows:

    pip install octave_kernel
    python -m octave_kernel.install

### Assignment
In this assignment you are expected to generate fibonacci numbers by **fast fibonacci transform** and plot the ratio of two succesive elements (we expect it to converge golden ratio). To see detailed explanation, look at [Fibonacci.ipynb](Fibonacci.ipynb). You should write your code into [Fibonacci.ipynb](Fibonacci.ipynb) and submit it as explained in [course-description](https://github.com/CMPE482-Spring2017-Bogazici/course-description).
