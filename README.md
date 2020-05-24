# datascience-math

A set of cheat sheets about mathematical topics frequently used in data science. Easy to search topics via the html page - [Math Cheatsheets for Data Science](https://shotahorii.github.io/datascience-math/).

## Getting Started

The cheat sheets are written in LaTeX on Jupyter notebook. No need to download, you can just view on GitHub. Search topics via the html page - [Math Cheatsheets for Data Science](https://shotahorii.github.io/datascience-math/).

## Run on your computer

Only prerequisites is a jupyter environment. If you have a Jupyter environment on you computer, you can run all notebooks here, without any specific libraries installed. Otherwise, below is an example environment. 

### Example Environment

#### Prerequisites
- docker installed 
- jupyter/minimal-notebook image is pulled by `docker pull jupyter/minimal-notebook`

#### Run 

`cd` to this directory, then type below. 

```
docker run --rm -p 8888:8888 -v "$PWD":/home/jovyan/work jupyter/minimal-notebook
```