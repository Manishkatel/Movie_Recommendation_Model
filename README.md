# Movie Recommendation System

This project demonstrates how to build a **Movie Recommendation System** using collaborative filtering techniques. The goal is to recommend movies to users based on their preferences and past interactions.

---

## **Objective**

The purpose of this project is to create a movie recommendation system using user ratings. The system suggests movies to users that align with their preferences, improving their movie-watching experience.

### **Key Features:**
1. **Collaborative Filtering**: We use collaborative filtering to recommend movies based on user preferences and movie ratings.
2. **Content-Based Filtering**: Additionally, content-based filtering is used to suggest movies similar to those the user has already liked.
3. **Hybrid Model**: Combining both collaborative and content-based methods for more accurate and personalized recommendations.

---

## **Dataset**

The dataset used in this project is the **MovieLens dataset**, which includes:
- **User Ratings**: Ratings provided by users for various movies.
- **Movies**: Information about the movies, such as title, genres, etc.

You can download the dataset from the following link:
[MovieLens Dataset](https://grouplens.org/datasets/movielens/)

---

## **Approach**

### **Steps:**
1. **Data Preprocessing**: Cleaning the data, handling missing values, and preparing it for model training.
2. **Collaborative Filtering**: Using matrix factorization techniques like **Singular Value Decomposition (SVD)** to identify patterns in user ratings.
3. **Content-Based Filtering**: Recommending movies based on content features (e.g., genres).
4. **Model Evaluation**: Evaluating the model’s performance based on how well it predicts the ratings or user preferences.

---

## **Setup and Installation**

To run this project on your local machine, follow these steps:

1. **Clone the repository:**
   ```
   git clone https://github.com/Manishkatel/Movie_Recommendation_Model.git
   cd Movie_Recommendation_Model
   ```
2. **Install dependencies as specified in notebook**
3. **Download the Dataset: You can download the MovieLens dataset from the MovieLens website.**
4. **Run the Notebook: Open the Movie_Recommendation_System.ipynb notebook and run the cells sequentially to preprocess the data, train the model, and generate recommendations.**

## Model Evaluation
The movie recommendation system is evaluated based on the following metrics:

-**Precision and Recall**: How well the model recommends relevant movies.
-**Mean Squared Error (MSE)**: Evaluating the prediction error for the ratings.

**Feel free to reach out for better model performance suggestions**
