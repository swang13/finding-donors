# finding-donors

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python.  The code should run with no issues using Python versions 3.*.

## Project Motivation<a name="motivation"></a>

This is the first project of Udacity Data Science Nanodegree. In this project, I employed several supervised algorithms to model individuals' income using data collected from the 1994 U.S. Census. The goal with this implementation is to construct a model that accurately predicts whether an individual makes more than $50,000


## File Descriptions <a name="files"></a>

There is one iPython notebook to showcase work related to this project. 
The census.csv contains the 1994 U.S. Census data used by this analysis.
visuals.py includes supporting code provided by Udacity for data visualizatioin.

## Results<a name="results"></a>

A Logistic Regression model is trained using 36,177 historical data points to predict whether an individual makes more than 50,000 dollars or not based on a few characteristics of that person, such as occupation, age, education level, gender, etc. The relationship between the features of a person and the likelihood of making more than $50,000 is learned by the logistic model by looking at these histocial data points.

The optimized model has an accuacy score of 0.8422, and an F-score of 0.6842 on testing data. The results from my optimized model are much better than the native predictor benchmarks, which has an cccuracy score of 0.2478 and an F-score of 0.2917


## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Credits must be given to Udacity for providing starting code and data for this project.  