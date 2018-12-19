# WeRateDogs-DataWrangling

Wrangling WeRateDogs
By Roberto Soriano

# Introduction #

This is the final project of the Udacity’s Data Analytics Nanodegree Data Wrangling course. Wrangling is all about taking unclean and untidy data and transforming it in data that we can use for data analysis and modeling. In this project we gather raw data from the WeRateDogs Twitter archive, using Twitter’s API, assess it, clean it and analyze it to find insights. The final result is used to make dog breed predictions using machine learning. 


## Project Details 

The WeRateDogs Twitter Archive, which contains Tweet-IDs and content information, was handed down for us to: 

Gather: extract the data programmatically. 
Assess: explore data to find insights and potential tidiness and structural issues.
Clean: format and structure data so that it could be used profitably.
Analyze: to find insights and use it to make predictions. 


## The Data

WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. The WeRateDogs’ Twitter archive contains the tweet and content information for over 5000  tweets. A CSV file with the data for these tweets was handed down to us to assess, wrangle and analyze. The dataset provided did lack some important pieces of information like the retweet count, favorite count, and sometimes it contained the incorrect names. Using the Tweet-IDs, we queried the Twitter API, using Python’s libraries like TweePy, Requests and others,  to extract the tweets original JSON data. We then used this extracted data to wrangle the dataset provided to us.


## Wrangling performed

Quality Issues
- Remove Retweets and retweet columns
- Names column contains many incorrect values
- Remove tweets with no images
- Create column for dog stage and remove the individual variable columns
- Improve tweet sources by source category
- Remove unnecessary columns
- Set the correct dtype for each variable
- replace "& amp;" with "&"

Tidiness issues
- Display full texts in dataframe columns 
- Join all three dataframes, the twitter archive, predictions and the tweet data.


## Analysis

Brief analysis performed, and insights discovered, are displayed in the “act_report”.

