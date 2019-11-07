# Quora_quationpairs_similarity
## Description:
* Quora is a place to gain and share knowledge—about anything. It’s a platform to ask questions and connect with people who contribute unique insights and quality answers. 
* This empowers people to learn from each other and to better understand the world. Over 100 million people visit Quora every month, so it's no surprise that many people ask similarly worded questions. 
* Multiple questions with the same intent can cause seekers to spend more time finding the best answer to their question, and make writers feel they need to answer multiple versions of the same question. Quora values canonical questions because they provide a better experience to active seekers and writers, and offer more value to both of these groups in the long term.

# Problem Statement and build ML model:
#### initially we have downoald dataset traindataset.csv  from kaggle source: https://www.kaggle.com/c/quora-question-pairs#evaluation
#### dataset contains 5 features(id, q1 id, q2 id, quation1 and quation2) and 1 class label(is dupliacate or not), according to thae dataset we could say it is 2 class  classification problem.class label  values implies quation pair is similar(is_duplicate = 1) or not similar(is_duplicate = 0). so that we can use  KPI(key performence indiacator is "Log-loss" and predict probablity that quations are duplicates.
#### quations changes over time so split our dataset using Time based splitting after that we have two important feature quation1 and quastion2 are contains text data so that we have to perform text preprocessing.
#### after the text preprocessing we have to perform Feature extraction(Feature Engineering) then apply classical Machine Learning models.

## Tools we have used:
* Python3
* Jupyter Notebook


## Required libraries:

 * Pandas: using for construct dataframes.
 * Numpy : using for some Numerical mathematical operations.
 * matplotlib&seaborn: using for visual tools.
 * Natural Language Processing
 * fuzzywuzzy: feature extraction(feature engineering) of text data.
 * Sklearn: this most useful for basing ml models.
 
 
 ### Acknowledgement:
 *  Applied AI course


