# BlogME-Keyword-and-Sentiment-Analysis

In this project we analyse news article data using pandas and find sentiment corresponding to every articles using Vader Library. 
## Pandas 
It is a software library written for the Python programming language for data manipulation and analysis. In particular, it offers data structures and operations for manipulating numerical tables and time series.

## Vader (Valence Aware Dictionary for Sentiment Reasoning)
It is an NLTK module that provides sentiment scores based on the words used. It is a rule-based sentiment analyzer in which the terms are generally labeled as per their semantic orientation as either positive or negative.

## Approach
1. Understand the data. 
2. Create a keyword flag function to find a given keyword in the article heading.
3. Add the keyword flag to dataframe.
4. Find out polarity score article using SentimentIntensityAnalyzer function from Vader Library.
5. Add the indentified sentiment namely positive, negative and neutral to the dataframe.
6. Convert the dataframe in excel format to make visualization.
7. Use tableau to create visualization of finding.
