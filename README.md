# Udacity--Wrangle-WeRateDogs-Twitter-Project
# Project Overview
In this project, my goal is to wrangle WeRateDogs Twitter data to create interesting and trustworthy analyses and visualizations.

# Resources needed for this project?
Python, plus the following libraries:
- Pandas
- NumPy
- Matplotlib
> I recommend installing Anaconda, which comes with all of the necessary packages, as well as IPython notebook.

# Project Motivation
Unpacking the data wrangling process namely:
- Gathering
- Assessing
- Cleaning
- Visualization
Python libraries NumPy, pandas, Matplotlib, Seaborn, requests, tweepy and json will be employed for easier data wrangling in python.

# Lessons Learn?
- I am acquainted with steps involved in a typical data analysis process.
- I have the ability to sought data from different sources and make them ready for analysis, including querying the twitter api and web scraping.
- Assessing the tidiness of a dataset using visual and programmatic assessment techniques.
- Cleaning untidy data using the Define Code Test Style.
- I am able to effectively communicate the results of my analysis
- I am able to use vectorized operations in NumPy and pandas to speed up my data analysis code
- I know how to use Matplotlib to produce plots showing my findings

# Project Details: Introduction & Dataset Description
The dataset under scope was the tweet archive of the Twitter user @dog rates,better known as WeRateDogs. WeRateDogs is a twitter_account that rates people's dogs with humorous comment about the dog.
These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc.

# Datasets
- [twitter-archive-enhanced.csv](data/twitter-archive-enhanced.csv)
- [image-predictions.tsv](data/image-predictions.tsv)
- [tweet-json.txt](data/tweet-json.txt)

# Data Wrangling
Wrangling the twitter data through the following steps:
- Gathering Data
- Assessing Data
- Cleaning Data
- Stroing, analysing and visualising the cleaned data
- Genrating a report on the various steps taken under the wrangling section

# Gather
Enhanced Twitter Archive data contains basic tweet data given by Udacity.
Twitter API to gather retweet count and favorite count, which are notable columns, additionally details about hashtags used.
Image Predictions File, containing the predicted breeds of dogs given by Udacity.

## Limitations:
Enhanced archive data contains basic tweet data (tweet ID, timestamp, text, etc.) of their tweets as they stood on August 1, 2017.
Only original ratings (no retweets) that have images are considered.

# Assess
Assess data for:

**Quality:** inconsistent data, inaccurate data, non-descriptive headers, missing values (NAN).
**Tidiness:** issues with structure that prevent easy analysis. Tidy data requirements: Each variable forms a column. Each observation forms a row. Each type of observational unit forms a table.

## Types of assessment:

- Visual assessment
- Programmatic assessment (used Pandas)

# Clean
Programmatic data cleaning process:

**Define:** convert the assessments into defined cleaning tasks.
**Code:** convert those definitions to code and run that code.
**Test:** test your dataset, visually or with code, to make sure cleaning operations worked.
