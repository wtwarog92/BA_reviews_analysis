## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Files content](#files-content)

## General info

This project is focused on reviewing and analysing reviews from Skytrax website.
The main idea was to provide some insight into the content of the reviews, using topic modelling, sentiment analysis, wordclouds.

The task was completed using Python.

## Technologies

Reviews were retrieved from the website using BeautifulSoup library and cleaned using Pandas.
Next, using NLTK library reviews were cleaned by removing stopwords.
After that, using SentimentIntensityAnalyzer, reviews ratings were checked and divided into 3 groups:
0 - 'negative ratings' (1-3 stars out of 10)
1 - 'neutral ratings' (4-7 stars out of 10)
2 - 'positive ratings' (8-10 stars out of 10)

To get insight into the content of the reviews wordclouds for negative and positive ratings were created.

## Files content

'BA_raw_data.ipynb' - contains the first stage of this project. Using BeautifulSoup and Pandas libraries reviews were dowloaded and saved.

'data_preparation_and_analysis.ipynb' - contains further cleaning data and analysis

'customer review BA - Task 1.pptx' - contains final "mini" presentation with analysis findings
