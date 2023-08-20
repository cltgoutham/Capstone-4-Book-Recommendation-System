# Capstone-4-Book-Recommendation-System
This is an Unsupervised Machine Learning project used to make a Book Recommendation System using collaborative filtering method.


The goal of this project is to develop a book recommendation system that provides personalized recommendations to users based on their preferences and interests. The system should take into account various factors such as the user's reading history, genre preferences, ratings, and other relevant information to generate accurate and relevant book recommendations.

(image)

**Introduction**

Recommender Systems are algorithms aimed at suggesting relevant items to users. Items can be books, movies to watch, text to read, products to buy, or anything else depending on industries. Recommender systems are really critical in some industries as they can generate a huge amount of income when they are efficient or also be a way to stand out significantly from competitors. During the last few decades, with the rise of Youtube, Amazon, Netflix, and many other such web services, recommender systems have taken more and more place in our lives.

**DATASET INFORMATION**

This dataset consist of 3 csv files:

1. Books : [Books.csv file](https://drive.google.com/file/d/1E_au771kKkNaXKNVZdgOyNdBqMy6E-cN/view?usp=drive_link)  This contain the information about the Book-Title, Authors, Publishers etc.
2. Ratings : [Ratings.csv file](https://drive.google.com/file/d/1aXuv5iRBUoJnOg-ige8Z6LkNnrm1BBCL/view?usp=drive_link) This contains the Rating information of the books given by different users.
3. Users : [Users.csv file](https://drive.google.com/file/d/178X7IbhhVV6Ha-dEHSxcDEyP8UTTSTNG/view?usp=drive_link) User information like Age, location is provided in this file.


# Approach to the Project

## 1. **Data Preprocessing**

**Books_Data**
* Dropping unnecessary columns
* Filling the null values
* Replacing the columns with correct values

**Rating_Data**
* Seperating Implicit rating and Explicit rating

**Users_data**
* Analysing Age column and Correcting
* Location column
* Outlier Treatment

## 2. **Merging the datasets**

## 3. **Data visualization**
* Analysing the data and visualizing with different plots.

  (image)

## 4. **Feature Engineering and Model Building**

* Popularity Based Recommender system on basis of
  - Average Rating
  - Authors
  - Publishers
* Collaborative Filtering Method
  - Creating Pivot table and Sparse matrics
  - NearestNeighbor Algorithm
  - KMeans Algorithm

* Created Dropdown to make the system easy accessible and interactive.

