# Movie-Recommender-using-Spark-MLlib
We are going to illustrate the power of Spark by using the "movielens" dataset, which contains 100k ratings for movies through 1997, and recommend movies to the user based on his previous ratings (just like Netflix would reccomend you movies to watch based on the movies you have already watched and obviously many more features which we will not be touching upon today). 

Today we will be using a machine learning model - collaborative filtering on the movielens dataset to obtain the desired output. The model is first trained on the ratings of the user we already have and based on those ratings we try and predict the movies which the user would like to watch.


**About the Data:**
MovieLens data sets were collected by the GroupLens Research Project at the University of Minnesota. This data set consists of:

•	100,000 ratings (1-5) from 943 users on 1682 movies

•	Each user has rated at least 20 movies

•	Simple demographic info for the users (age, gender, occupation, zip)


**Requirements:**
Apart from the obvious basic conceptual understanding of Hadoop, we require the following:

•	Hadoop Ecosystem (HDFS, YARN, Spark, etc.)

•	Hortonworks Sandbox to administer the Hadoop Ecosystem

•	Python

•	Oracle VM VirtualBox Manager

•	Putty
