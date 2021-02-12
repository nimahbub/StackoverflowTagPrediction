# StackOverflow-Tag-prediction
<img src = 'https://github.com/nimahbub/stack-overflow-tag-prediction/blob/main/images/stackoverflow.png'>
## Description
>Stack Overflow is something which every programmer use one way or another. Each month, over 50 million developers come to Stack Overflow to learn, share their knowledge, and build their careers. It features questions and answers on a wide range of topics in computer programming. The website serves as a platform for users to ask and answer questions, and, through membership and active participation, to vote questions and answers up or down and edit questions and answers in a fashion similar to a wiki or Digg. As of April 2014 Stack Overflow has over 4,000,000 registered users, and it exceeded 10,000,000 questions in late August 2015. Based on the type of tags assigned to questions, the top eight most discussed topics on the site are: Java, JavaScript, C#, PHP, Android, jQuery, Python and HTML.


#### Problem statement :
>Given the Title and body of a question on Stack overflow, predict the tags associated with the question.

#### Types of ML Problem :
> Multi-label Classification Problem


### DATASET  OVERVIEW:
> Source: https://www.kaggle.com/c/facebook-recruiting-iii-keyword-extraction/data
All of the data is in 2 files: Train and Test.

Train.csv contains 4 columns: Id,Title,Body,Tags

- Id - Unique identifier for each question
- Title - The question's title
- Body - The body of the question
- Tags - The tags associated with the question (all lowercase, should not contain tabs '\t' or ampersands '&')

> **Note** : - In this project I have taken only 10923 data points to analysis fast. Dataset I have used in this project: https://github.com/nimahbub/stack-overflow-tag-prediction/blob/main/strackoverflow.csv


#### Getting Started
> Start by downloading the project and run "stackoverflow.ipynb" file in ipython-notebook.

#### Tools:
You need to have installed following softwares and libraries in your machine before running this project.

1. Python 3
2. Anaconda: It will install ipython notebook and most of the libraries which are needed like sklearn, pandas, seaborn, matplotlib, numpy and scipy.


### Note :
> In this project I have used only  10923 data points to train model in which only few tags were present as target values. So, this model will not give appropriate tags for all questions. To get the best outcome we have to train our model with whole dataset. 





   
