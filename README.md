#### Movie-Recommender-using-Spark-MLlib
We are going to illustrate the power of Spark by using the "movielens" dataset, which contains 100k ratings for movies through 1997, and recommend movies to the user based on his previous ratings (just like Netflix would reccomend you movies to watch based on the movies you have already watched and obviously many more features which we will not be touching upon today). 

Today we will be using a machine learning model - collaborative filtering on the movielens dataset to obtain the desired output. The model is first trained on the user ratings we already have and based on those ratings we try and predict the movies which the user would like to watch.


##**About the Data:**
MovieLens data sets were collected by the GroupLens Research Project at the University of Minnesota. **u.item** consists of information about the items (movies) and **u.data** consists of:

•	100,000 ratings (1-5) from 943 users on 1682 movies

•	Each user has rated at least 20 movies

•	Simple demographic info for the users (age, gender, occupation, zip)


##**Requirements:**
Apart from the obvious basic conceptual understanding of Hadoop, we require the following:

•	Hadoop Ecosystem (HDFS, YARN, Spark, etc.)

•	Hortonworks Sandbox (Ambari) to administer the Hadoop Ecosystem

•	Python

•	Oracle VM VirtualBox Manager

•	Putty


##**Result:**
As you can see, we were successfully able to obtain recommendations, which may not be perfect but are quite close as the user seemed to liked sci-fi movies and the model predicted a few sci-fi movies. This project was primarily done to show a project on Spark. The code took hours to run on Python alone, but we obtained the results on Spark inside 20 seconds which shows the true power of Spark and why it is so popular.

##**Inspiration:**
I would like to thank Frank Kane whose course on Hadoop enabled me get a good understanding of how to work with Spark and other Hadoop frameworks.
