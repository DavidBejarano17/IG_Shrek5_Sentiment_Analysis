# Instagram Shrek 5 Sentiment Analysis

## Project Overview

This sentiment analysis project aims to found and resolved some questions and isnigths between the trend post on Instagram of the new Shrek movie (Shrek 5). I want to uncover the reasons of the anger of the people, their perspectivrd and what the sentiment analysis can told us about of the new film that will be released on 2026.

![Image](https://github.com/user-attachments/assets/37a8bf80-22f6-4d0a-b8e9-b0ba9dd43d85)

## Data Sources

For scrapping the comments on Instagram I used a scrapping tool to get the data and its called (IG Export & Scraper).


![Image](https://github.com/user-attachments/assets/cc3e1bbf-b835-4fdf-b650-5a8d3fb28826)


For 100k comments of the Shrek post, I only scrab 10K, this because the Meta´s policy don´t allow public to download so much quantity of data unless you use the official API of meta and get the permissions.

**Note:** Web scraping may violate Instagram's Terms of Service, so please use caution if collecting your own data.

Instagram Data: The primary dataset used for this project sentiment analysis is the "shrek_commets_INST.csv" 

## Tools 

- Jupyter Notebook
  - ETL
  - Data Cleaning
  - Filtering
  - EDA
  - Text preprocessing
  - Tokenization

    
- Power Bi
  - Filtering
  - EDA
  - Build interactive dashboard


 ## Exploratory Data Analysis
 
Exploring the sentiments of the comments and answer kew questions, like:

- Distribution of the sentiment score (Neg, Pos, Neu) ?
- Distribution of the comments by region ?
- Most used emojis ?
- Most common complaints ?
- Reasons for people anger ?
- Most used hashtags ?


## Develop

### - Translating the comments


Using Jupyter Notebook, it was extracted the dataset and transformed applying some functions and tools to translate the comments that are in other languages. The reasons are because we can get better insigths, after VADER has detected comments text in English.

You can view the Jupyter Notebook: https://github.com/DavidBejarano17/IG_Shrek5_Sentiment_Analysis/blob/main/Translation_of_comments.ipynb


### - Sentiment Analysis

In this section, after extracting, cleaning and transforming data to create a column of the comments in English. In the following Jupyter notebook we can found some insights and queries that will be usefull to the analysis.

You acan view the Jupyter Notebook:
https://github.com/DavidBejarano17/IG_Shrek5_Sentiment_Analysis/blob/main/data_sent_analysis.ipynb










  
