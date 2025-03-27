# Instagram Shrek 5 Sentiment Analysis

## Project Overview

This sentiment analysis project aims to uncover isnigths and resolve questions related to the Instagram trend of the new Shrek movie (Shrek 5). The goal is to understand the reasons behind people's sentiments, perspectives and whats sentiment analysis can tell us about the upcoming film set to be released in 2026.

![Image](https://github.com/user-attachments/assets/37a8bf80-22f6-4d0a-b8e9-b0ba9dd43d85)

## Data Sources

To scrape the comments on Instagram I used a  tool called (IG Export & Scraper).


![Image](https://github.com/user-attachments/assets/cc3e1bbf-b835-4fdf-b650-5a8d3fb28826)


For 100k comments of the Shrek post, I only scrab 10K, due to Meta´s policy which restricts public access to large quantities of data unless you use the official Meta API and obtain the necessary permissions.
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

- What is the distribution of sentiment scores (Negative, Positive, Neutral)?
- What is the distribution of comments by region?
- What are the most used emojis?
- What are the most common complaints?
- What are the reasons for people's anger?
- What are the most used hashtags?


## Develop

### - Translating the comments


Using Jupyter Notebook, the dataset was extracted and transformed by applying functions and tools to translate the comments in other languages. This helps in gaining better insigths after VADER detects comments text in English.

You can view the Jupyter Notebook: https://github.com/DavidBejarano17/IG_Shrek5_Sentiment_Analysis/blob/main/Translation_of_comments.ipynb


### - Sentiment Analysis

After extracting, cleaning and transforming the data to create an English comments column, we can find insights and queries useful for the analysis in the following Jupyter Notebook 

You acan view the Jupyter Notebook:
https://github.com/DavidBejarano17/IG_Shrek5_Sentiment_Analysis/blob/main/data_sent_analysis.ipynb




## Power Bi Dashboard

Take a look of the Dashboard: https://github.com/DavidBejarano17/IG_Shrek5_Sentiment_Analysis/blob/main/Instagram_Shrek5_Sentiment_Analysis_Dashboard.pdf








  
