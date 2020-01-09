# Disaster_tweets_kaggle
python script for the NLP kaggle competition on "Disaster_tweets"

## content
this python script is designed to work on the public datasets from kaggle
you can find the datasets here: https://www.kaggle.com/c/nlp-getting-started/overview

## comments
the pipeline for NLP treatment in this file here as follows:
1. Load data
2. FillNA
3. Remove all non letters elements from the text streams
4. merge the train and test datasets
5. NPL actions on text variables: split , Stem, Join, Vectorize
6. then we train and test 3 algorithms: SVC, NaiveBaies, LogisticRegression
7. Save prediction
