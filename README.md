# Seattle-Airbnb Data Analysis
Exploratory Data Analysis and Sentiment Analysis on Seattle Airbnb Dataset using Tableau and Python

## Motivation
This project is part of the requirement for Data Scientist Nanodegree on Udacity to follow the CRISP-DM (Cross-industry standard process for data mining) of [Seattle Airbnb Dataset on Kaggle](kaggle.com/airbnb/seattle/data)
1. The project aims to analyze few aspects of the Airbnb renting scene in Seattle such as: the effect of location on price, occupancy pattern, earnings and reviews by host, and what guests say about their experience, etc. Although the dataset is old, the analysis method and tool used is universal and can be reused for newer or other datasets using Tableau visualization
2. It also analyze review sentiment with Python NLTK, TextBlob and VaderSentiment
3. A blog post is written on Medium to summarize the findings to non-technical audience

## Dataset
There are 3 csv datasets:
1. listing: provide individual listing and its attributes: host information, listing information, pricing, review
2. calendar: occupancy and availability of listings in 365-day period from Jan 2016 - Jan 2017
3. reviews: 85k reviews for all listings from 2009-2016

## Installation/Requirement
1. Tableau dashboards and visualizations can be downloaded from [Tableau Public Repo](https://public.tableau.com/profile/anh.chu#!/vizhome/Seattleairbnb/EDA). The file can be read with Tableau version 2019.2 and above
2. To run the Python code, you will need to install necessary packages: Seaborn, NLTK, Wordcloud, Textblob and VaderSentiment using `pip install` or `conda install`. The code is written in Python3

## License
MIT 

