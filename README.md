
## 🚀 About Me


Hi. I am Ribhu Bose. I am aspiring Data Analyst
## 🛠 Skills
Python, MySQL, Advanced Excel, Power BI, Machine Learning,
Data Analysis, Statistical Modeling, Numpy, Pandas, Seaborn, Matplotlib,
Google Sheets, MS Word, PowerPoint.


![Logo](https://assets.skyfilabs.com/images/blog/spam-sms-detection.webp)


# SMS Spam Detection

In today’s world there is a big need of analyzing the data as it has lot of information that goes un-noticed. In order to detect such pattern, the Machine Learning techniques are used. In this project, we are going to work with a dataset which has the data of SMS which are collected to classify them into SPAM or HAM. So, if a message is sent by a real user then it should be tagged as Ham or if it is by a machine for advertisement purpose then it should be tagged as SPAM.


## PURPOSE

In daily life, we receive lot of messages from different sources and those messages might be arriving from a machine just for the advertisement purpose. The mobile user gets irritated because of such messages and may even ignore a real message from a known person. In order to avoid such cases, we are going to classify these SMS messages into two categories as SPAM or HAM.
## Installation

Numpy, Pandas, Seaborn, Matplotlib
    
## SCOPE

The project is made on Google Colaboratory. This application is an easy to use application as the user need to run the complete program and the user will get the accuracy of each model. Since, there is no un-labelled data, we are going to divide the data in Train and Test dataset. Test dataset is used for validating our model performance. Also, in case in future we have some new dataset which is not labelled then we can classify them too.
## OVERVIEW

This document will give you an easy walk over through the application and act as a guide with easy steps to use and maintain the application. Detailed overview of each feature and design is covered below in the System Overview. This application does not involve any database, but this is a future aspect of this application in case there is a need to store the labelled data, the flow of application is explained with data flow in use case diagram under System Architecture section. In the end, a visual look and feel of this application with the flow of application is shown. This application act as a perfect medium to classify the SMS messages with text data using NLP techniques.
## SYSTEM OVERVIEW

The project involves the text data which cannot be classified by basic modeling techniques and hence we are using NLP techniques. Natural Language Processing helps us to bridge the gap of text data with numerical data which is needed to run by the machine. It also helps us to neutralize the dirty text data into a simpler form. We are removing Stop words punctuations, commonly appearing terms using TF-iDF (Term Frequency inverse Document Frequency). The major steps that are involved in order to classify the data are as follows. Each step is described with Code Snippet.
## Importing Libraries:

First thing we are going to do is to import the important libraries. Since we are working on Text data, we have imported NLTK for text analysis. Also, for data visualization, we have used matplotlib, Seaborn library.
## Read Dataset:
Next thing we need to do is to input the dataset we need to work on. The data is located in our current working directory which is Downloads in this case. The command dataframe.head() help us in checking the first 5 lines of our dataframe.
## Describe the dataset and the label column:

The data should be understood correctly and hence, we are going to describe the whole dataset and also the label column.


## Machine Learning Steps – Basic Text pre-processing steps:

This step is our first important step and we are first going to do some text pre-processing in order to clean the dataset before we input it to our models.

So, we have converted all the text into lower case and then we removed the punctuations from our dataset. Finally, we removed the stop words form our dataset.
## Stemming each term using Porter Stemmer:

In order to make sure that our model predict the data better, we are going to stem our words into its stem form.
## Split the dataset into train and test:

Since, we do not have any train and test dataset split already, we are going to split the dataset into train and test. The test dataset is used for validating our models.
## Training Models Logistic Regression:
Let’s start training our models. The first model we are going to use is Naïve Bayes. In the last line, we have also shown the Confusion Matrix,
Accuracy Score,Classification Report.
## Support Vector Classifier:
SVMs are always considered as good model for text classification. So, let’s train the SVM too.
## Decision Tree:

Similarly, we are going to train our data with Decision Tree.
## Naive Bayes:

Similarly, we are going to train our data with Naive Bayes.
## K Nearest Neighbour:

Similarly, we are going to train our data with K Nearest Neighbour.
## Random Forest:

Also, we are going to use Random Forest as generally it gives higher accuracy then other models.
## Classification Report for all the models:

As we are done with all the models we wanted to use, let’s check the classification report of these models.