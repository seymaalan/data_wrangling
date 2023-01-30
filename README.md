
## Overview
I gathered, cleaned, and analyzed an interesting dataset on Python: WeRateDogs tweets. First, let me introduce you to this famous Twitter account. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because "they're good dogs Brent." WeRateDogs has over 4 million followers and has received international media coverage.

## Datasets
I worked on three datasets:

-Enhanced twitter dataset: The dataset that I have worked on contains basic tweet data (tweet ID, timestamp, text, etc.) for all 5000+ of their tweets as they stood on August 1, 2017. Using post text, dog names, ratings and dog stages are extracted. I downloaded the given csv file for the dataset.

-Retweet and favorite counts dataset: I downloaded retweet and favorite counts for the tweets from Twitter's database. Actually, there is an issue so I had to use prepared json file.

-Predicted breeds dataset: Using images from tweets, a machine learning algorithm predicted the breed of the dog, and I also used this dataset. With request library, I created a request and download dataset as tsv file.
