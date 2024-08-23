---
layout: page
title: Anaconda environment setup guide
nav_exclude: true
description: >-
    Instructions on how to setup anaconda environment
---

# *Anaconda* environment setup guide

This tutorial provides a brief overview of how to set up a new conda environment 
and install the packages we will need for the course.

{: .note }
> This setup is the most minimal setup and easy to debug in case of issues.

{: .important }
> This course is not about tooling.
> Hence, no support is given in case of issues with a student's individual 
> setup.
> There are plenty of resources freely available on the internet.

### Prerequisite

This tutorial assumes a working installation of the *Anaconda* python 
distribution. 
If you haven't installed it yet, please follow the official 
[installation instructions](https://docs.anaconda.com/anaconda/install/) on 
their website.

### 1 - Create a dedicated environment for the Course

The following command creates an anaconda environment named `my_environment`.

```shell
conda create --name my_environment
```

{: .note }
> Instead of `my_environment`, you can choose whatever name you want for an 
> environment.
> It can be also the name of the course, so you can distinguish between the 
> individual, necessary setups.

To verify whether you environment has been installed correctly run the 
following command and check whether the environment is shown in the list. 

```shell
conda env list
```

After the environment has been created successfully we still need to switch 
from `base` environment to the `my_environment` environment.

```shell
conda activate my_environment
```

### 2 - Install important packages

Below you will find a list of packages which I would recommend to install. 
Execute the following commands to install the packages **in the newly 
created environment**.

```shell
conda install -c anaconda jupyter
conda install -c anaconda numpy
conda install -c anaconda pandas
conda install -c anaconda matplotlib
conda install -c conda-forge seaborn
conda install -c anaconda scikit-learn
```

During the course we may need further packages as well. 
The instruction of installation will then be done within the lecture material.

At a later stage we will also need PyTorch which can also be installed with 
conda. 
However, the exact command you have to execute depends on your machine's 
capabilities.
Therefore, I will only refer you to the 
[official installation instructions](https://pytorch.org/get-started/locally/).


### 3 - Launch a Jupyter Notebook

To launch the Jupyter notebook run the following command inside the directory 
which should become our working directory. 
Executing the command will launch the Jupyter's web editor.

```shell
jupyter notebook
```

Copy & Paste the link shown in terminal in our browser or simply click on the 
link in the shell to launch your browser (if supported by our terminal).


### Alternative: a professional IDE
In case you prefer with an IDE instead of the web editor, 
[PyCharm](https://www.jetbrains.com/pycharm/) 
also provides supports for Jupyter Notebooks.

{: .tip }
> If you want to use all capabilites of PyCharm, apply for a free educational 
> license.
> With this, you will have full access to all cool tools, like remote 
> development, notebooks, the scientific mode, etc.
> To apply, visit 
> [this site](https://www.jetbrains.com/community/education/#students).