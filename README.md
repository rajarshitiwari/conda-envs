# conda-envs


This repository lists a set of python environments that I plan to maintain and keep track of.
When I am testing, or using python in a number of projects, I use virtual environments to separate the dependencies.
Very quickly, the number of environments became very large. While many people keep them in the code repo itself, I
like to maintain a list of relatively commonly used environments separate.

I use `micromamba` instead of `conda` to keep things a bit leaner. I use it to create a bare environment with desired
python version and pip. Then I install required packages with pip and `requiremnts.txt`. If the environment largely
depends only on conda packages, a similar file can be kept to create the desired environment.


