# Sparkify

Capstone Project, Udacity Data Science Nanodegree
Github Repo: https://github.com/Nuzulu/Udacity-Sparkify

# Files in this Repository

1. Notebook:    Sparkify.ipynb
2. HTML:        Sparkify.html
3. Readme file: README.md

## Overview
Sparkify, is a Udacity dataset designed to be similar to dataflows expected from a big data music service such as Spotify or Pandora. It is a log of user activity, with demographic information, ratings, music browsing habits etc. The aim of the project is to analyse this data, and via the Pyspark library for python, apply machine learning models in an attempt to accurately predict CHURN (the likelihood of a customer ending the service).

A blog of this project can be found at https://medium.com/@nuzulu/data-exploration-and-machine-learning-with-spark-d6c1ab31c6d

## Data
mini_sparkify_event_data.json

## Packages:
- PySpark
- Pandas
- Seaborn
- Matplotlot.pylpot

## Models:
- Logistic Regression
- Gradient Boosted Trees
- Support Vector Machines
- Random Forest

## Process Steps:
1. Load data and cleanse
2. Perform Exploratory Analysis
3. Define CHURN variable
4. Feature Engineering
5. Modelling
6. Evaluation

## Summary of Results

The best model identified was Random Forest, and against the final validation data, an F1 score of .8 and an accuracy of .82 was achieved.
