# Tweets-NLP

The objective of this project is to perform word frequency analysis. This link provides Twitter data of Elon Musk from 2010-2022. For analysis we consider the years `2017-2021` (last 5 complete years). Each year has thousands of tweets. We assume each year to be a document (all the tweets in one year will be considered as a document) 
1. We Compute the term frequencies for each year after normalizing them on a scale of [0, 1]. We exclude the stopwords. 
2. We Show the top 10 words (for each year) by highest value of word frequency. 
3. We plotted a histogram of word frequencies for each year 
4. Demonstrated Zipf’s law by plotting log-log plots of word frequencies v. rank for each year 5. Use TF-IDF to calculate and show the 5 most “important” words for each year

Dataset:

https://www.kaggle.com/datasets/ayhmrba/elon-musk-tweets-2010-2021?resource=download&select=2017.csv
