# Zomato-Restaurant-and-Reviews-Analysis
Zomato Unsupervised ML analysis 


### Introduction
============================
Zomato is one of the largest food delivery app in the world. Restaurant and users from around the world enjoy different cuisines and share their reviews and experiences on this platform. Founded in 2008, Zomato has now expanded into 24 different countries and has its presence in almost 10,000 cities.

Having such a large user base, it is important for this platform to make the data of restaurants presented to the users in more organised format so that users can filter restaurants based on reviews, rating, pricing etc.

Platforms such as zomato continue to grow in trend and this is because the information of all restaurants present in one single place makes it very convienent for the users to choose their restaurants based on cuisines they like, their budget and also based on popularity.

In this project we explore how different restaurants compare to each other based on rating, price category, number of cuisines they offer etc. We also see how different users rate different restaurants and what is their average spending. We perform EDA on the two datasets given and plot charts to visualise insights. Then we perform some preprossesing on review corpus of words to prepare our data for modelling. After that we perform aglomerative hierarchical clustering on restaurants data and perfrom LDA topic modeling to find out the probable words for each topics. Then we use visuallization tools such as pyLDAvis to see how different words are related to each topic.

Therefore we are going to we are going to explore the restaurants in Indian cities and see how users like to review them.

### Shape of Datasets
============================
The restaurant rating dataset has 105 rows and 6 columns
The restaurant reviews dataset has 10000 rows and 7 columns
