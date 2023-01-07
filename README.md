# Netflix-Movies-and-Tv-Shows
NLP , Clustering

## 📖Introduction
Netflix, the world’s largest on-demand internet streaming media and online DVD movie rental service provider.it Founded August 29, 1997, in Los Gatos, California by Marc and Reed. It has 69 million members in over 60 countries enjoying more than 100 million hours of TV shows and movies per day Netflix is the world’s leading internet entertainment service with enjoying TV series, documentaries, and feature films across a wide variety of genres and languages. I was curious to analyze the content released in Netflix platform which led me to create these simple, interactive, and exciting visualizations and find similar groups of people.

## Project Statement :

Built Recommendation system based on Similar Genres and Movies which Users prefer to filter and recommend only those user is most likely to watch.

#### Problem Describtion: 
This dataset consists of tv shows and movies available on Netflix as of 2019. The dataset is collected from Flixable which is a third-party Netflix search engine.<br>
In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset.<br>
Integrating this dataset with other external datasets such as IMDB ratings, rotten tomatoes can also provide many interesting findings.<br>




#### About the Data :
We have the data of which contains details of customers like id , age, gender and also contains the details of the customers vehicle 


**Dataset info**

* 1.Number of records: 7787

* 2.Number of features: 12

### **Features information:**

The dataset contains features like:

* **show_id :** Unique ID for every Movie / Tv Show<br>
* **type :** A Movie or TV Show<br>
* **title :** Title of the Movie / Tv Shows<br>
* **director :** Director of the Movie<br>
* **cast :** Actors involved in the movie / show<br>
* **country :** Country where the movie / show was produced<br>
* **date_added :** Date it was added on Netflix<br>
* **release_year :** Actual Release year of the movie / show<br>
* **rating :** TV Rating of the movie / show<br>
* **duration :** Total Duration - in minutes or number of seasons<br>
* **listed_in :** Generes<br>
* **description:** The Summary description<br>

<h2> :book: K-means Clustering </h2>

K-Means Clustering is an Unsupervised Learning algorithm, which groups the unlabeled dataset into different clusters. Here K defines the number of pre-defined clusters that need to be created in the process, as if K=2, there will be two clusters, and for K=3, there will be three clusters, and so on.

The k-means clustering algorithm mainly performs two tasks:

Determines the best value for K center points or centroids by an iterative process.

Assigns each data point to its closest k-center. Those data points which are near to the particular k-center, create a cluster.


### **Execution Instruction:**

1) train.py

Then, the train.py file must be executed, which leads to the production of the model.txt file. At the beginning of this file, the dataset for training has been imported so that the functions defined in it can be used.

2) test.py

Finally, the test.py file must be executed to create the result.txt and evaluation.txt files. Just like the train.py file, at the beginning of this file, the dataset for test  has been imported so that the functions defined in it can be used.

**Project Work flow**
----------------------------

1. Importing Libraries<br>
2. Loading the dataset<br>
3. Data Summary <br>
4. Data Cleaning & Data Analysis<br>
5. Feature selection<br>
6. Implementing different clustering methods<br>
7. Conclusion<br>

## **Conclusion**
Build K-means Clustering Model to analysis create Netflix movies and tv showsrecommendation systems . Optimal number of Clusters was found by Elbow method
and silhouette score . On analysis Netflix has more focus on TV shows versus movies . Also, video content on Netflix's catalogue was clustered into Three clusters achieved through K-mean.

##**References**##

1)Analytical Vidya

Available:https://www.analyticsvidhya.com/blog/2021/11/understanding-k-means-clustering-in-machine-learningwith-examples/

2)AlmaBetter Mentor and Coach




