# **Introduction-to-Data-Science-Project-Anime-Recommendation-System**

**Data Science Project:
Recommendation System for Anime
Group Members List:**


Muhammad Bilal Tahir F2018054042 (Group Leader)

Muhammad Abdullah Younus F2018054005

Muhammad Arsalan Shahzad F2018054013

Muhammad Bilal F2018054046

**Machine Learning:**

It is the subfield of computer science that gives computers the ability to learn without being explicitly programmed.

**A few types of Machine Learning:**

Regression

Classification

Clustering

Recommendation systems

**What are recommendation systems:**

Recommendation systems are a collection of algorithms used to recommend items to users based on information taken from the user.

In this notebook, we will explore recommendation systems based on collaborative filltering and implement a simple version of a recommendation system.

**Dataset chosen:**

We have chosen the following two datasets:

anime.csv

rating.csv

Anime.csv holds the information about almost 12,000 animes, for example; anime name, genre, episode list, anime type etc.

Rating.csv holds the information of ratings from around 100,000 users, for example; ratings of users against the respected anime_id.

**Source of Datasets:**

www.Kaggle.com

**What each column represents in the anime dataset:**

anime_id: id number of each anime

name: title of the anime

genre: category

type: separates the anime into categories eg tv, movies, OVA, etc

episodes: total number of episodes

rating: -1–10, lowest to highest

members: number of users that rated an anime

**What each column represents in the rating dataset:**

user_id: represents Id of users

anime_id: represents anime Id's

rating: rating of anime given by each user

**Table of Contents:**
Data Loading

Preprocessing (Data Wrangling)

Data Visualization & Groupby

Recommendation System (Collaborative filtering)

Machine Learning Techniques (Multiple Linear Regression)
