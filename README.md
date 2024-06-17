# YouTube-Transcript-Data-Analysis

## Read more about project
https://medium.com/@kakarvardaan/1339df454a47

## Set up Account with YouTube API Client 
https://developers.google.com/youtube/v3/quickstart/python


## Requirements for data cleaning and analysis:
- nltk
- matplotlib
- pandas
- google_auth_oauthlib
- googleapiclient
- youtube_transcript_api
- umap
- hdbscan
- plotly
- scikit-learn
- gensim
- spacy

I have used multiple libraries where I could have used just a single one for learning purposes, feel free to play with the modules and explore.

Open up fetch_transcripts.ipynb and edit CSV_NAME and YOUTUBE_CHANNEL_ID to be the ID of the YouTube channel you want to download the captions for, then run the cells.

This will open up a popup asking you to authorise the app to fetch data. Accept the terms and give the permissions.

Once it runs, it should generate a .csv with a bunch of details for each video entry. If there is an existing .csv with the same name as CSV_NAME (I have provided 'mkbhd.csv' as a start), it will just fetch data from the .csv and not fetch fresh details.

Ideally, order of execution of files:
> etch_transcripts.ipynb

> review.ipynb

> plot.ipynb

> grouping.ipynb