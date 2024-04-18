# AspectAnalyzer

## Team Members
Aparna Gopalakrishnan, Mexi Liang, Zoey Xu

## Introduction
We intend to study Yelp reviews through Aspect-Based Sentiment Analysis (ABSA) to 
discover the aspects or dimensions and their sentiments in the review text. With respect to restaurant reviews, aspects mean dimensions like 'food quality', 'ambiance' etc.. The goal of our project is twofold: For customers searching for a specific restaurant we want to provide a list of top aspects along with their sentiment score for that restaurant. For business owners, we want to provide a comprehensive solution for improving aspects of reviews written for their restaurants, and this would be accomplished by finding similar restaurants which have high ratings for these aspects and providing most useful reviews associated with these aspects. 

## Repo Layout
### /data 
folder that contains data files we used in our modeling and result files that we conducted through manual evaluation of our model.
### /1_Data_Preprocessing
folder that contains the code to preprocess the Yelp reviews data
### /2_Model
folder that contains the code that includes all our models

    /1_Topic_Modeling
    Within the 2_Model folder we have this folder which includes all the code associated with Topic Modeling, namely LDA, NMF and BERTopic
    
    /2_ABSA
    Within the 2_Model folder we have this folder which includes all the code associated with Aspect Based Sentiment Analysis, namely SetFit ABSA and Deberta based ABSA models
    
    /3_Recommender_Feature
    Within the 2_Model folder we have this folder which includes the approach that finds the similar restaurant 
    
### 3_Evaluation_Visualization
folder that contains the evaluation of the various models and visualtization for Deberta models

### 4_Result_files
folder that contains the result files from the BERTopic model

### requirement.txt
```bash
# install the required packages for our project
pip install -r requirement.txt
```
