[![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://badges.mit-license.org)

[<img src="https://avatars1.githubusercontent.com/u/36938641?s=200&u=b2d470fe66acc157d8ca8cb3fb815dee47d4466d&v=4" align="right" />](https://github.com/machine-learning-experiments)

# The simpsons script generator by history

This project makes a new and unique script from Moe's Tavern by script history, using recurrent networks.

> See the [jupyter notebook](https://github.com/machine-learning-experiments/the-simpsons-script-generator-by-history/blob/master/dlnd_tv_script_generation.ipynb)

### Motivation

Understand recurrent networks.

### Built With

- [Python 3](https://www.python.org/download/releases/3.0/) - Language
- [Anaconda](https://www.anaconda.com/what-is-anaconda/) - Python Data Science Platform 
- [Jupyter notebook](http://jupyter.org/) - Web application that allows to create documents that contain live code

### Dataset

A history of 262 scenes from Moe's Tavern.

## Getting Started

### Prerequisites
1. Download and install [Anaconda](https://www.anaconda.com/download/)
2. Update Anaconda
> ``` 
> $ conda upgrade conda 
> $ conda upgrade --all 
> ```

### Install

1. Clone and enter into the project's root directory by command line
> ``` 
> $ git clone https://github.com/machine-learning-experiments/the-simpsons-script-generator-by-history
> ```
2. Create and activate enviroment
> ``` 
> $ conda create --name the-simpsons-script-generator-by-history python=3
> $ source activate the-simpsons-script-generator-by-history
> $ conda install jupyter
> $ conda install -c conda-forge tensorflow numpy
> ```
3. Start jupyter notebook
> ``` 
> $ jupyter notebook 
> ```
4. Your browser will open showing a list of files, click on the  [dlnd_tv_script_generation.ipynb](https://github.com/machine-learning-experiments/the-simpsons-script-generator-by-history/blob/master/dlnd_tv_script_generation.ipynb) notebook file

## Author

[Lorival Smolski Chapuis](https://github.com/lorival)
> This project was developed during the [deep-learning](https://br.udacity.com/course/deep-learning-nanodegree-foundation--nd101) nanodegree from [Udacity](https://br.udacity.com/) 