# internship-project
# Google Play Store Analytics Project

## Project Overview

This project focuses on analyzing Google Play Store apps and user reviews using Python. The goal is to understand app performance, user behavior, and trends through data analysis and visualization.

## Dataset

The project uses the following datasets:

* Play Store Data (app details such as category, rating, installs, price)
* User Reviews Data (user feedback and reviews)


## Objectives

* Analyze app categories and their distribution
* Study user ratings and installs
* Perform sentiment analysis on user reviews
* Identify trends in revenue and app updates
* Build an interactive dashboard for visualization


## Tools and Technologies

* Python
* Pandas
* NumPy
* Plotly
* NLTK
* Scikit-learn
* Jupyter Notebook


## Data Cleaning and Preparation

* Removed missing values from important columns
* Filled remaining missing values using mode
* Removed duplicate records
* Converted columns like Reviews, Installs, and Price into numeric format
* Processed Size column into a uniform format



## Feature Engineering

* Created Revenue column (Price × Installs)
* Applied log transformation on Installs and Reviews
* Grouped ratings into categories (Top rated, Average, etc.)
* Extracted Year from the Last Updated column


## Sentiment Analysis

* Used VADER sentiment analyzer from NLTK
* Calculated sentiment scores for user reviews
* Analyzed distribution of positive and negative sentiments


## Visualizations

The project includes the following visualizations:

* Top categories on Play Store
* App type distribution (Free vs Paid)
* Rating distribution
* Sentiment distribution
* Installs by category
* Revenue by category
* Updates over time
* Genre distribution
* Ratings comparison (Free vs Paid apps)
* Relationship between updates and ratings


## Dashboard

An interactive dashboard is created using Plotly and exported as an HTML file. The dashboard can be opened in a web browser and includes multiple charts with basic insights.


## Key Insights

* Most apps are free on the Play Store
* Ratings are generally high for most apps
* Some categories have significantly higher installs
* Revenue varies across categories
* User sentiment is mostly positive
* Frequent updates do not always lead to higher ratings


## How to Run

1. Install required libraries:
   pip install pandas numpy plotly nltk scikit-learn

2. Run the Python file or Jupyter Notebook

3. Open the generated dashboard.html file in a browser


## Project Files

* Training.py / Training.ipynb (main code)
* dashboard.html (output dashboard)
* Dataset files

## Author

NANDINI BANSAL
