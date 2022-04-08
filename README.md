# My First EDA Project : Investing in the King County Housing Market

In this repository we will have a look at the King County House Price Data from May 2014 - May 2015.
Our stakeholder is interested in buying und selling houses for the highest possible profit. Therefore things as social responsibility or a sustainable urban development are counterproductive. Her mantra: 'If I don't do it, someone else will.'.
To match her interest in the housing market we need to provide data where to find cheap objects with high profit margins.

## The data
You can find the data here:
https://geodacenter.github.io/data-and-lab/KingCounty-HouseSales2015/

## Virtual Environment

This repo contains a requirements.txt file with a list of all the packages and dependencies you will need. Before you install the virtual environment, make sure to install postgresql if you haven't done it before.

```Bash
brew update
brew install postgresql
```

In order to install the environment you can use the following commands:

```Bash
pyenv local 3.9.8
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```

## Setup

One of the first steps when starting any data science project is to create a virtual environment. For this project you have to create this environment from scratch yourself. However, you should be already familiar with the commands you will need to do so. The general workflow consists of... 

* setting the python version locally to 3.9.8
* creating a virtual environment using the `venv` module
* activating your newly created environment 
* upgrading `pip` (This step is not absolutely necessary, but will save you trouble when installing some packages.)
* installing the required packages via `pip`

