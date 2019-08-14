## Welcome to the Natural Language Processing in Python Tutorial!

We will be going through several Jupyter Notebooks during the tutorial and use a number of data science libraries along the way. The easiest way to get started is to download Anaconda, which is free and open source. When you download this, it comes with the Jupyter  Notebook IDE and many popular data science libraries, so you don’t have to install them one by one.

Here are the steps you’ll need to take before the start of the tutorial:

### 1. Download Anaconda
I highly recommend that you download [the Python 3.7 version](https://www.anaconda.com/download/).

### 2. Download the Jupyter Notebooks
Clone or download this [Github repository](https://github.com/adashofdata/nlp-in-python-tutorial), so you have access to all the Jupyter Notebooks (.ipynb extension) in the tutorial. **Note the green button on the right side of the screen that says `Clone or download`.** If you know how to use Github, go ahead and clone the repo. If you don't know how to use Github, you can also just download the zip file and unzip it on your laptop.

### 3. Launch Anaconda and Open a Jupyter Notebook

*Windows:*
Open the Anaconda Navigator program. You should see the Jupyter Notebook logo. Below the logo, click Launch. A browser window should open up. In the browser window, navigate to the location of the saved Jupyter Notebook files and open 0-Hello-World.ipynb. Follow the instructions in the notebook.

*Mac/Linux:*
Open a terminal. Type ```jupyter notebook```. A browser should open up. In the browser window, navigate to the location of the saved Jupyter Notebook files and open 0-Hello-World.ipynb. Follow the instructions in the notebook.

### 4. Install a Few Additional Packages

There are a few additional packages we'll be using during the tutorial that are not included when you download Anaconda - wordcloud, textblob and gensim.

*Windows:*
Open the Anaconda Prompt program. You should see a black window pop up. Type `conda install -c conda-forge wordcloud` to download wordcloud. You will be asked whether you want to proceed or not. Type `y` for yes. Once that is done, type `conda install -c conda-forge textblob` to download textblob and `y` to proceed, and type `conda install -c conda-forge gensim` to download gensim and `y` to proceed.

*Mac/Linux:*
Your terminal should already be open. Type command-t to open a new tab. Type `conda install -c conda-forge wordcloud` to download wordcloud. You will be asked whether you want to proceed or not. Type `y` for yes. Once that is done, type `conda install -c conda-forge textblob` to download textblob and `y` to proceed, and type `conda install -c conda-forge gensim` to download gensim and `y` to proceed.

If you have any issues, please email me at adashofdata@gmail.com or come talk to me before the start of the tutorial.
