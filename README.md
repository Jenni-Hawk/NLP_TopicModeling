# NLP_TopicModeling
Natural Language Processing and Topic Modeling with a breadth of algorithms

# Client / Background
- Since Twitter is a major conversation platform, The Washington Post would like to understand the topics that are trending within the January 6th Committee Hearings to get potential story ideas.

# Key Questions to Answer
- What topics were most tweeted about during the Oct 13th hearing?
- What was the primary topic associated with Trump?
- What was the sentiment of the primary topic associated with Trump?

# Data
- 35,000 Tweets / Retweets

# Solution Path
#### Twitter API
- Configured & Tested
#### Get Tweets
- [Via Tweepy Used Twitter API](https://github.com/Jenni-Hawk/NLP_TopicModeling/blob/main/1_Acquire_Data_PreProcess.ipynb)
#### Preprocessing
- Removed special characters, punctuation, etc
#### Topic Modeling 
- Unsupervised learning and rules based approaches
- [LSA with CountVectorizer & LSA with TF-IDF](https://github.com/Jenni-Hawk/NLP_TopicModeling/blob/main/2_TopicModel_LSA_CountVec_TDIF.ipynb)
- [LDA with CountVectorizer](https://github.com/Jenni-Hawk/NLP_TopicModeling/blob/main/3_TopicModel_LDA_CountVec.ipynb)
- [LDA with Bigrams](https://github.com/Jenni-Hawk/NLP_TopicModeling/blob/main/4_TopicModel_LDA_Bigrams.ipynb)
#### Sentiment Analysis with VADER
- Applied to entire conversation and individual topic

#### Findings
Check out the presentation

#### Tech Tools Used
- Tweepy
- NLTK
- Sklearn
- Gensim
- VADER
- Regex
- Pandas

