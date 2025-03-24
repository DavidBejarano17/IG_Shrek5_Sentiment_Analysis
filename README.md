# Instagram Shrek 5 Sentiment Analysis

## Project Overview

This sentiment analysis project aims to found and resolved some questions and isnigths between the trend post on Instagram of the new Shrek movie (Shrek 5). I want to uncover the reasons of the anger of the people, their perspectivrd and what the sentiment analysis can told us about of the new film that will be released on 2026.

![Image](https://github.com/user-attachments/assets/37a8bf80-22f6-4d0a-b8e9-b0ba9dd43d85)

## Data Sources

For scrapping the comments on Instagram I used a scrapping tool to get the data and its called (IG Export & Scraper).

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

## Develop

### - Translating the comments

![Alt text](https://www.bing.com/images/search?view=detailV2&ccid=D5qLFs4t&id=6B3845E373170E50C7EE0D54D7B236BBAD58F39D&thid=OIP.D5qLFs4t18g8BbQiPXhOOwHaE8&mediaurl=https%3A%2F%2Fwww.englishtospanishraleigh.com%2Fcms%2Fwp-content%2Fuploads%2F2019%2F02%2FGoogle-Translate-English-to-Spanish.webp&cdnurl=https%3A%2F%2Fth.bing.com%2Fth%2Fid%2FR.0f9a8b16ce2dd7c83c05b4223d784e3b%3Frik%3DnfNYrbs2stdUDQ%26pid%3DImgRaw%26r%3D0&exph=334&expw=500&q=translation&simid=607998328841445441&FORM=IRPRST&ck=22B444B561ADBF5542251F8A3FFCF009&selectedIndex=2&itb=0&cw=1375&ch=671&ajaxhist=0&ajaxserp=0)


Using Jupyter Notebook, it was extracted the dataset and transformed applying some functions and tools to translate the comments that are in other languages. The reasons are because we can get better insigths, after VADER has detected comments text in English.

You can view the Jupyter Notebook: https://github.com/DavidBejarano17/IG_Shrek5_Sentiment_Analysis/blob/main/Translation_of_comments.ipynb











  
