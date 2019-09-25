# Seattle-Airbnb Data Analysis
Exploratory Data Analysis and Sentiment Analysis on Seattle Airbnb Dataset using Tableau and Python

## Motivation
This project is part of the requirement for Data Scientist Nanodegree on Udacity to follow the CRISP-DM (Cross-industry standard process for data mining) of [Seattle Airbnb Dataset on Kaggle](kaggle.com/airbnb/seattle/data). The project aims to analyze few aspects of the Airbnb renting scene in Seattle such as: the effect of location on price, occupancy pattern, earnings and reviews by host, and what guests say about their experience, etc. 

The project consists of 4 parts: 
- Part 1: Data Visualization in [Tableau](https://public.tableau.com/profile/anh.chu#!/vizhome/Seattleairbnb/EDA) 
- Part 2: Price Prediction using Linear Regression and Random Forest Regression
- Part 3: Review sentiment with Python NLTK, TextBlob and VaderSentiment
- Part 4: [A blog post](https://medium.com/@anhchu1291/seattle-airbnb-renting-scene-a-closer-look-powered-by-data-f7498ae57262) on Medium to summarize the findings to non-technical audience 


## Project Files
1. Main files:
- Seattle_Airbnb.ipynb: Jupyter notebook file with codes for 3 parts of the analysis
- Seattle airbnb.twbx: Tableau package workbook for the data visualization portion

2. Data files: 
There are 3 csv datasets:
- listing.csv: provide individual listing and its attributes: host information, listing information, pricing, review
- calendar.csv: occupancy and availability of listings in 365-day period from Jan 2016 - Jan 2017
- reviews.csv: 85k reviews for all listings from 2009-2016
- geocoding.csv: include the geocoding for Seattle neighborhood for data visualization in Tableau

3. Helper files:
- detectEnglish.py: to detect non-English comments, I use a helper function called detectEnglish provided by http://inventwithpython.com/hacking (BSD Licensed)
- dictionary.txt: English words dictionary for detectEnglish.py
- house3.png, house4.png: image files for sentiment wordclouds 
- Images folder: keeps all the images used in the blog post on Medium 

## Installation/Requirement
1. Tableau dashboards and visualizations can be downloaded from [Tableau Public Repo](https://public.tableau.com/profile/anh.chu#!/vizhome/Seattleairbnb/EDA). The file can be read with Tableau version 2019.2 and above
2. The code is written in Python3. To run the Python code, you will need to install necessary packages: Seaborn, NLTK, Wordcloud, Textblob, VaderSentiment, scikitlearn and its dependencies using `pip install` or `conda install`. 

## Reference and Credit
Below resources have helped me in some parts of this project, and I would like to thank these authors and articles:

1. [Visualizing Data with Pairs Plots in Python - Will Koehrsen](https://towardsdatascience.com/visualizing-data-with-pair-plots-in-python-f228cf529166)
2. [A Complete Exploratory Data Analysis and Visualization for Text Data - Susan Li](https://towardsdatascience.com/a-complete-exploratory-data-analysis-and-visualization-for-text-data-29fb1b96fb6a)
3. Hands-on Machine Learing with Scikit-Learn and TensorFlow - Aurelien Geron

## License
Under MIT license which means it's an open/public project, please feel free to download, make changes and give me feedback
