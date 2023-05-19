## Datasets

### Blodgett

The file "Blodgett_50k_IDs.csv" contains the IDs of 50,000 Tweets that we used in our reproduction, that were still available via the Twitter API at publication time. You can use the Twitter API to retrieve these tweets with the notebook "02_Retrieve_twitter_data.ipynb". However, some of the Tweets may have become unavailable (if they are deleted or removed from Twitter) since publication time.

To create this list of Tweet IDs, we downloaded the file "TwitterAAE-full-v1.zip" from [http://slanglab.cs.umass.edu/TwitterAAE/](TwitterAAE: Research on African-American English on Twitter
). From this dataset, we selected the IDs of Tweets that have a high probability (greater than 90%) of being AAE, according to the Blodgett model - this probability is given in the data files. There were about 500,000. We used the Twitter API to retrieve the first 50,000 Tweets that are still available. 


### DWMW17

We retrieved the [https://github.com/t-davidson/hate-speech-and-offensive-language/blob/master/data/labeled_data.csv]("labeled_data.csv") file from [https://github.com/t-davidson/hate-speech-and-offensive-language](Automated Hate Speech Detection and the Problem of Offensive Language
) and named it "Dwmw17.csv".

### FDCL18 

We downloaded the FDCL18 dataset from [Intersectional Bias in Hate Speech and Abusive Language Datasets](https://github.com/jaeyk/intersectional-bias-in-ml) and named it`fdcl18.csv`.
