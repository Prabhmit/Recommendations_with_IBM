# Portfolio Excercise: Udacity - Recommendations with IBM

# Table of Contents

1. Installations and package requirement
2. Project Motivation
3. Project Components and File Descriptions
4. Instructions
5. Licensing, Authors and Acknowledgments

# Installations and package requirement

The code is in Python 3.7.6. The Python libraries applied are numpy, pandas, pickle, matplotlib, sklearn and nltk. 

# Project Motivation

The primary objective of this excercise is to analyze the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles they will like.

# Project Components and File Descriptions

The datasets are user-item-interactions.csv and articles_community.csv. The Recommendations_with_IBM.ipynb file is a Jupyter notebook which includes the relevant code for this project. top_5.p, top_10.p,top_20.p are scripts to test the model output. user_item_matrix.p is the user item matrix for the dataset required for Matrix Factorization component (file could not be added to github due to file-size constraints).

The project has five components: 

## Exploratory Data Analysis

In this component the data was explored numerically and visually and certain modifications were made to it for the next components.

## Rank Based Recommendations

In this part the most popular articles were found based on the most interactions to build a rank based recommendations system. 

## User-User Based Collaborative Filtering

In this component, similar users were found based on dot product similarity. The articles viewed by similar users were used to make personal recommendations for the users. 

## Content Based Recommendations (Extra - not required)

In this part, NLP was applied to compute the cosine similarity between articles based on their description to find similar articles to develop a content based recommendation system.

## Matrix Factorization 

In this component, matrix factorization was used to make article recommendations to the users on the IBM Watson Studio platform.

# 4. Instructions

1. Run the cells in the Recommendations_with_IBM.ipynb notebook.

# 5. Licensing, Authors and Acknowledgments

Experimental Design and Recommendations, Data Scientist Nanodegree Program, Udacity, https://www.udacity.com/course/data-scientist-nanodegree--nd025

Recommendations with IBM, Udacity, https://www.udacity.com/course/data-scientist-nanodegree--nd025

scikit-learn, Machine Learning in Python - https://scikit-learn.org/stable/index.html
