---
title: Search Engine
description: Built a Search Engine Website that employs the TFIDF Ranking Algorithm.
author: Ahaan Kanaujia
date: 2020-09-23T15:13:13.021Z
tags:
  - Python
  - NLTK
  - spaCy
  - Flask
  - WikipediaAPI
  - React.js
  - TailwindCSS
---
### Back End:

A Wikipedia web-crawler downloads documents for searching. A TFIDF DataFrame is created for each word present in every search document. Implemented 3 different searching algorithms: cosine similarity algorithm, Jaccard index similarity algorithm, and the Ratcliff-Obershelp sequence based algorithm that returns the most relevant Wikipedia document based on a tokenized query. Also used the Levenshtein Distance edit based distance algorithm to widen the scope of the query, which accounts for minor errors in spelling and grammar.

<br>

### Front End:

Created a Flask backend API for processing requests to the search algorithms. It is accompanied by a basic React.js page with a text box for entering the query. The most relevant Wikipedia pages are then displayed in a list format. 

<br>

![Site Functionality](/static/img/searchengine.png "Site Functionality")

<br>

**Libraries Used: NLTK, spaCy, NumPy, pandas**

<br>

<u>**[GitHub](https://github.com/AhaanKanaujia)**