# WeRateDogs Twitter Data Wrangling & Analysis
This project was completed as part of Udacity's Data Analyst Nanodegree.
## Introduction
> [WeRateDogs](https://twitter.com/dog_rates?ref_src=twsrc%5Egoogle%7Ctwcamp%5Eserp%7Ctwgr%5Eauthor) is a Twitter account that rates people's dogs with a humorous comment about the dog. The account was started in 2015 by college student Matt Nelson, and has received international media attention for its popularity.<br> 
In This Project, most of the necessary data was provided by udacity, however not all the data was gathered from udacity, I made use of the Twitter API to gather additional data, in addition, Udacity ran the images on WeRateDogs's account through a neural network to generate three predictions for each image. For each prediction, there is also data on the confidence and whether the prediction is a type of dog breed.

# Research Questions:
- What are the top 3 most used languages?
- What are the top 5 most common ratings?
- Which source text has the most retweets?
- How did the retweet count and favorite count improve over time?
- What predicted breed of dog has the highest retweet count and favorite count?
- Does an increase in the text length lead to an increase in the favorite count?

# Table of Contents
- `wrangle_act.ipynb:` the Jupyter Notebook version for the cleaning and merging of the dataset.
- `act_report.ipynb:` the Jupyter Notebook version for analysis and visualization.
- `act_report.html:` the HTML version of act_report.ipynb
- `Dataset:` the folder containing all the datasets used for this report
- `Requirements.txt`: the required python libraries

# Installation and Configuration
Download Anaconda at https://www.anaconda.com/download/ and install the libraries in the requirement.txt file using PIP

Install Jupyter Notebook by running the following command:
```
conda install jupyter notebook
```
or
```
pip install jupyter notebook
```

Then launch the Jupyter Notebook to view the .ipynb file.
