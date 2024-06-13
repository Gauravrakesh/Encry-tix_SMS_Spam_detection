
# SMS spam detection using Naive Bayes Machine Learning Algorithms




## Python Libraries used
Pandas  
Numpy  
matplotlib  
seaborn  
sklearn  
nltk











## Data Acquisition
https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset  

### dataset info  
5572 rows and 2 columns
## Data Preprocessing  
### Convert the spam & ham(Legitimate) target column values into 1 & 0  

 using LabelEncoder  

### transform the sms description into cleaned Data

use the Countvectorizer to convert the string text into matrix form 
 
## Machine Learning Models  

In this we will use classification based supervised machine learning algorithm  


Multinomial Naive Bayes  
Gaussian Naive Bayes  
Bernaulli Naive Bayes


## Results  
Accuracy_score by MultinomialNB = 0.96  
Accuracy_score by BernoulliNB = 0.97  
Accuracy_score by GaussianNB  = 0.89
