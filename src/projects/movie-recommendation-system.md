---
title: Movie Recommendation System
description: Built a Machine Learning Content Based Movie Recommendation System
author: Ahaan Kanaujia
date: 2022-03-14T07:22:00.292Z
tags:
  - Python
  - NLKT
  - scikit-learn
  - pickle
  - Streamlit
---

### Concept:

Every movie in the database is assigned a piece of text, called tags, which is created by combining the cast, crew, genre, overview, and synopsis text of movie. 

<br>

Next, a bag of words is created, which include all the words present in all the tags assigned to all 5000 movies. After that, we compare every movie's tags with the bag of words and create a vector of 0's and 1's depending on if a word in a movie's tags is found in the bag of words. 

<br>

And finally, we compare vectors of 2 movies to create a list of the most similar movies, which are displayed on the website by utilizing a TMDB API to grab movie data. 

<br>

### Back End:

The website employs the bag of words machine learning model to make movie recommendations based on user input in the form of content and tags consisting of movie details. It uses a 5000 movies database and the TMDB API to pull movie specifics for displaying and running the model to make comparisons. 

<br>

### Front End:

Streamlit was used as the front end of the website. It displays the movie poster, synopsis, audience score, release date, cast, crew, and a brief overview of the top 10 most similars movies. The website is hosted online on the heroku platform.

<br>

**Libraries Used: scikit-learn, NLTK, NumPy, pandas, Streamlit**

**<br>**

<strong><u>[GitHub](https://github.com/AhaanKanaujia/Movie-Recommendation-System)

<br>

<strong><u>[Website](https://movies-rec-system-ahaank.herokuapp.com/)