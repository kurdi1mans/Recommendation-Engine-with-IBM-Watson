# Recommendation-Engine-with-IBM-Watson

This project is part of the Data Science Nano-Degree from Udacity.

### Table of Contents

1. [Motivation](#motivation)
2. [Installation](#installation)
3. [File Descriptions](#files)
4. [Instructions](#instructions)


## Motivation <a name="motivation"></a>

This project is part of the Data Science Nano-Degree from Udacity.
The purpose of this project is to showcase an example of Recommender Engine that utilizes different approaches (e.g. Knowledge Based, Content Based, and Collaborative Filtering Based) for recommendations.

The approach utilized in the Collaborative Filtering approach here uses the Singular Value Decomposition approach on simplified user-item interaction data. Furthermore, it also touches base on the training and testing of the SVD artifacts.


## Installation <a name="installation"></a>

The code in this repository requires a Jupyter Notebook and a python installation with the following libraries available: pandas, numpy, matplotlib, project_tests, pickle, and seaborn. The easiest way to get all of these is to install them through Anaconda https://www.anaconda.com/.

## File Descriptions <a name="files"></a>

- Recommendations_with_IBM.ipynb: is our main file containing all the analysis, training, and testing code for the user-articles interactions.
- Recommendations_with_IBM.html: the final version (readonly) of the previous Jupyter notebook file containing the results of the analysis, training, and testing.
- data folder: contains the all datasets used in the Jupyter notebook
	- articles_community.csv: contains data for articles on which the analysis to be conducted.
	- user-item-interactions.csv: is our main dataset which contains information about the interactions between users and articles.
- top_5.p, top_10.p, top_20.p: contain user_item matrices that are used briefly in the Jupyter notebook for some analysis.


## Instructions <a name="instructions"></a>

- Once you have your Jupyter Notebook ready. You only need to run the Recommendations_with_IBM.ipynb. It contains all the needed code for analysis, training, and testing.
