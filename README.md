# An Analysis of the IMDB Top 50 Best films from 2015 - 2019
##### This project presents an in depth analysis for IMDB movies in the past 5 years using data from multiple sources such as IMDB website, user reviews and tweets. 

## 1 - The IMDBDataCleaningAnalysis & IMDBScraper Notebooks contain:
##### * IMDB list Data Scraper built using beautifulsoup
##### * Cleaning, Processing of Data using Pandas dataframes, regex
##### * Dealing with multiple categorical variables such as genre, handled by get_dummies() and inner joined into our dataframe
##### * Some key insights/analysis of the genres in relation to movie budgets, and gross earnings. Visualized using matplotlib
##### * Correlation observation using corr() and seaborn heatmap visualization
##### * Data Exported to csv, which was further analyzed and presented on Tableau Desktop


## 2 - The ReviewsImdb Jupyter Notebook:
##### * Adds Number of Reviews field, and Review Page URLs to each record
##### * Scrapes 25 reviews for each movie using beautifulsoup, and stores them in a csv file.


## 3 - The TweetsImdb Jupyter Notebook:
##### * Makes use of twitter API and tweepy to query movie names and return tweets for each movie.
##### * Tweets were cleaned using regex and stored in pandas dataframe.
##### * Tweet Sentiment was obtained using TextBlob library.
##### * Analyzed tweet sentiment distribution of movies, and most frequently occurring words using matplotlib. Tweet Vocabulary was used to visualize a wordcloud.
##### * Returned tweet data was stored in csv for further analysis.


## 4 - Visualizations
##### Tableau Dashboard Links:
[Analysis of Movie Data](https://public.tableau.com/views/IMDBTop2502015-2019/Whatdoesittaketobeagreatmovietoday?:display_count=y&:origin=viz_share_link)

[Analysis with User Reviews](https://public.tableau.com/views/IMDBUserReviewAnalysis/TrendsforIMDBUserReviews?:display_count=y&:origin=viz_share_link)

## - Hasan Zafar
