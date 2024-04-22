# cs285

I use Sergey Levine's Berkeley [course](http://rail.eecs.berkeley.edu/deeprlcourse/) homeworks as the basis to teach deep RL even better :)

Each homework consists in a notebook where everything is built from scratch and thoroughly explored.

## Installation

* [Download Anaconda](https://www.anaconda.com/products/distribution)
    * MacOS M1s should probably use the [miniconda installer](https://github.com/conda-forge/miniforge/)
* `conda create -n py39 python=3.9`
* `conda activate py39`
* `pip install -r requirements.txt`
* [Install Jupyter](https://jupyter.org/install)

## Run

* `jupyter notebook`
* `tensorboard --logdir runs`

## Misc

* Turn gifs into infinite loops:
    * Get [gifsicle](https://www.lcdf.org/gifsicle/)
    * `gifsicle -bl <path to gif>`