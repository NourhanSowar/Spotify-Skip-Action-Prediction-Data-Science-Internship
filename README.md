# Spotify-Skip-Action-Prediction-Data-Science-Internship
Music providers are also incentivized to recommend songs that their users like in order to increase user experience and time spent on the platform. Machine learning in the context of music often uses recommender system. There hasn’t been much research on how a user’s interaction with music over time can help recommend music to the user.

# The project is divided into multiple stages: #

## 1- Dataset ##

*  Chose public spotify dataset which contains (Session data -Track features)
   
   **Check the dataset paper through this link: https://arxiv.org/pdf/1901.09851.pdf**
   
## 2- Track Features & Session Data ##

In this, I have impleneted on dataset : 
*   1- Preprocessing on Data.
*   2- Data Wrngling (Handling Missing Data, Handling Categorical Data)
*   3- Feature Engineering
*   4- Exploratory data analysis (EDA)


## 3- Machine Learning Models ##

  In this, I have Implemented some ML models to predict skip Action and check f1_score by choose skipped Column as target value:
  
  *  1- RandomForestClassifier
  *  2- XGBClassifier
  *  3- DecisionTreeClassifier
 
 And chosen DecisionTreeClassifier as its high accuracy.
 
 
## 4- Machine Learning Deployment ##

In this, Using Falsk to create web application to predict the output of the model

**Let's check Web App Link : 
http://ae49-34-125-221-85.ngrok.io **



