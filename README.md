<<<<<<< HEAD
# Exoplanet Exploration

![exoplanets.jpg](Images/exoplanets.jpg)

## Background

Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system.

To help process this data, you will create machine learning models capable of classifying candidate exoplanets from the raw dataset.

In this homework assignment, you will need to:

1. [Preprocess the raw data](#Preprocessing)
2. [Tune the models](#Tune-Model-Parameters)
3. [Compare two or more models](#Evaluate-Model-Performance)

- - -

## Instructions

### Preprocess the Data

* Preprocess the raw dataset prior to fitting the model.
* Perform feature selection and remove unnecessary features.
* Use `MinMaxScaler` to scale the numerical data.
* Separate the data into training and testing data.

### Tune Model Parameters

* Use `GridSearch` to tune model parameters.
* Tune and compare at least two different classifiers.

### Evaluate Model Performance

Compare the performance of two or more classifiers to determine the best model performance.

- - -

## Resources

* [Exoplanet Data Source](https://www.kaggle.com/nasa/kepler-exoplanet-search-results)

* [Scikit-Learn Tutorial Part 1](https://www.youtube.com/watch?v=4PXAztQtoTg)

* [Scikit-Learn Tutorial Part 2](https://www.youtube.com/watch?v=gK43gtGh49o&t=5858s)

* [Grid Search](https://scikit-learn.org/stable/modules/grid_search.html)

- - -

## Hints and Considerations

* Start by cleaning the data, removing unnecessary columns, and scaling the data.

* Try a simple model first, and then tune the model using `GridSearch`.

- - -

## Submission

* Create a Jupyter Notebook and host the notebook on GitHub.

* Include a README.md file that summarizes your assumptions and findings.

* Submit the link to your GitHub project to Bootcamp Spot.
=======
# DeepBoardGameLearning

## Goal:

Application of Keras to create a Machine Learning Model to predict the popularity of a board game based on BoardGameGeek(BGG) Stats and Amazon Pricing.

## Steps 

### Scraping (100+ games)

Use beautifulsoup to scrape the BGG xml api and use Amazon api for useful information that can be used to train the machine learning model.

### Data Cleaning

Match the data collected by both sources into a Pandas dataframe

### Model Decision

Find which type of model will work for this task.

### Model Calibration

Find the configuration that will make the most accurate model
>>>>>>> 5d13d27a0a4dd477ba76d6caeeba5bf61e20d738
