# ETL 

This repo serves as the ETL project on Russion Troll Tweets, with contributions by Dyna Wilston, Rob Creel, Rigo Aguado, Maria Ugaz. The project aggregates Russion Troll Twitter data downloaded from Twitter and from Kaggle.

## Extract 

We extracted the data by downloading the files located at 

https://www.kaggle.com/fivethirtyeight/russian-troll-tweets/download

https://storage.googleapis.com/twitter-election-integrity/hashed/2018_10/ira/ira_users_csv_hashed.zip

https://storage.googleapis.com/twitter-election-integrity/hashed/2018_10/ira/ira_tweets_csv_hashed.zip

CSVs from the unzipped files are stored in the Resource directory.

## Transform

Transformation is handled in the `russiantrolls.ipynb` notebook.


## Load
Loading is also handled in the jupyter notebook.
