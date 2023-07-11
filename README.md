# Emotion Classification from Tweets

## Problem Statement

An emotion classification problem. Given a tweet or short text, the goal is to predict the emotion category the text expresses. There are 6 emotion categories: anger, fear, joy, love, sadness and surprise.

## Dataset

The dataset contains English tweets annotated with one of the 6 emotion categories. It consists of:

- 416,809 tweets in total, split into:
 - Train: 416,809 tweets   
 - Validation: 2,000 tweets
 - Test: 2,000 tweets

- Each tweet has:
 - `text`: The tweet text  
 - `label`: The emotion category, an integer from 0 to 5 representing one of the 6 emotions.   

The dataset has imbalanced label distributions, with some emotions being more common than others. The exact distributions will be analyzed in the task.

The tweets are short, consisting of around 20 words on average. The exact average length will be calculated in the task.

## Objective

- Load the dataset from json files.
- Analyze basic statistics:
  - Number of tweets in each split   
  - Sample tweets and their labels   
  - The 6 label categories 
  - Label distributions in the splits using plots   
  - Average tweet length in words in the splits
- Classify the emotions using BERT model.
