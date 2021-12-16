# Book Recommendation System 

# Abstract
The goal of this project was to build a recommendation system to help users choose the right book for them at the lowest time. I worked on the data from Kaggle, by using the pivot table and transforming it into a matrix using sparse with a User-based Collaborative Filtering using the nearest neighbors algorithm model to recommend the 5 nearest neighbors. After that, I worked on visualizing and communicating my results using Powerpoint.

# Design
Building a suggestion system helps to build a friendly relationship between the user and the system, and if the system is used in a library site, sales will increase because of the ease of access for users to books that match their interests

# Data
This project comtains of three datasets which are: books, users and ratings
 •	The books dataset is containing 271360 entries, 5 columns
 •	The user's dataset is containing   278858 entries, 3 columns
 •	Ratings dataset is containing 526356 entries, 3 columns

# Algorithms
- Feature Engineering
  - Select columns from the datasets and merge it to be one dataframe
   - Selecting subsets of the users we need just the users whos ratings more than 200 ratings
   - Merge ratings with books
   - merge the the popular book with the users and ratings
   - Select the books that have received more than 50 ratings
   
- Praper the data for modeling
  - Create a pivot table to find the similarity between users
  - Convert the pivot table to the sparse matrix
 
- Models
  - Nearest neighbors (Classification) model, using a brute algorithm.
  - To make a prediction I will use the result of the nearest neighbors model into the K nearest (Clustering ) model. 
  
- Final KNN algorithm: matrix features 
  suggest 5 nearst title book for user similirity

- input: 'Harry Potter and the Chamber of Secrets (Book 2)'
- Predict suggestion: 1. Harry Potter and the Chamber of Secrets (Book 2)
      	              2. Harry Potter and the Prisoner of Azkaban (Book 3)
        	            3.Harry Potter and the Goblet of Fire (Book 4)
                      4.Harry Potter and the Sorcerer's Stone (Book 1)
                      5.Exclusive
  # Tools
    - Numpy and Pandas for data manipulation
    - Scikit-learn for modeling
    - Matplotlib and Seaborn for plotting
    - powerpoint for the presentation
    
  # Communication
   This is a slides for the details of the project [book recommendation system slides](https://github.com/shadenalmangour/project/blob/main/book_recommendation_system.pdf)
               
