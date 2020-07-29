---
layout: post
published: false
title: 'K Nearest Neighbors: The Tutorial'
---
## A New Post

Today, I would like to talk about K-Nearest Neighbors. Easier known as KNN. This happens to be known as one of the simpler classification algorithms and is happens to be one of the most used in learning algorithms. This method is preffered by many in the industry because of its ease of use and low calculation time. 

I know many of you are wondering, well what is KNN? KNN is a model that classifies data points based on the points that are most similar to it. KNN uses test data to make an educated guess on what an unclassified point should be classified  as. 

Planning with a KNN Classifier algorithm goes as this:

**1)** Get a clean dataset. You don't want any missing values or mixes

**2)** You will need to find a point to classify. It has to have the same number of features.

**3)** You need to find the K closest elements from the dataset to the point in question. The K is usually an odd number so it avoids any ties. 

**4)** Now you want to classify that point based on the classification of its neighbors. 

The steps 1&2 will require you to do feature engineering and data cleaning. Feature engineering is the process of using domain knowledge to extract features from raw data via data mining techniques. These features can be used to improve the performance of machine learning algorithms. Data cleaning is the process of detecting and correcting or removing inaccurate records from a record set, table, or database and refers to identifying incomplete, incorrect, inaccurate or irrelevant parts of the data and then replacing, modifying, or deleting the dirty or coarse data.

Step 3 is when we find the K closest elements to the point and it is the **main** part of this algorithm. There are multiple ways to calculate the distance in Data Science. For me, the most straightforward way is the **Euclidean Distance**. The calculation for Euclidean is the **square root of the Sum of Squares of the Differences between the two points.** I know I definetely won't remember that in my head but it's an easy concept. Here is an example of the formula shown below.

![RtnTY.jpg]({{site.baseurl}}/img/RtnTY.jpg)

![distance-formula-between-two-points-example.gif]({{site.baseurl}}/img/distance-formula-between-two-points-example.gif)

Now that you have an idea, I can begin to show you how we code this distance method in Python.

![sorry.png]({{site.baseurl}}/img/sorry.png)


Here is my test with an easy dataset and a reference point: 

![distance.png]({{site.baseurl}}/img/distance.png)

Now that we have a working Euclidean Distance function, we can now move on and iterate through to find the K-Nearest Neighbors to our point. Now, since KNN models require datasets to be stored, our fit method is simply pulling the cleaned data into an array. Then, we will move the classification feature to the last element in each row. 



