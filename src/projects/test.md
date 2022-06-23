---
title: Search Engine
description: "Built a Search Engine Website that employs various Ranking Algorithms. "
author: Ahaan Kanaujia
date: 2020-09-23T15:13:13.021Z
tags:
  - Python
  - PyTorch
  - NLTK
  - spaCy
  - Flask
  - React.js
  - TailwindCSS
---
### Back End:

Employs different ranking algorithms such as the word based statistical  TFIDF, token based matching Jaccard Index, sequence based Ratcliff-Obershelp algorithms to return relevant documents based on a query. 

<br>

Users can upload documents from their computer to the website and select a specific algorithm or choose to run the best algorithm selector. 

<br>

Utilizes the Levenshtein Distance algorithm which widens the scope of a query to account for minor errors in spelling and grammar. Creates multiple queries, similar to the one entered by the user. 

<br>

An Artificial Neural Network, trained using the Gradient Descent and the doc2vec similarity algorithm, determines the ideal ranking algorithm based on the length of the query, reducing search latency by 60%.

<br> 

### Front End:

Created a Flask backend for processing requests and queries to the ranking algorithm and a RESTful API, which serves data in a JSON format.

<br>

Accompanied by a basic React.js and Tailwind CSS page with a text box for entering the query and an endpoint to upload documents to the website. The most relevant documents are then displayed in a list format.

<br>

**Libraries Used: NLTK, spaCy, NumPy, pandas**