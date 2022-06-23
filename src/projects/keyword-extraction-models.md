---
title: Keyword Extraction using Text Rank
description: Implemented a Keyword Extraction Method based on PageRank
author: Ahaan Kanaujia
date: 2022-03-14T02:01:20.997Z
tags:
  - Python
  - Machine_Learning
  - NLTK
  - spaCy
---
<br>

### Working of Text Rank:

In Text Rank, a piece of text is tokenized and annotated with part of speech tags – a preprocessing step that is required to enable application of syntactic filters. 

<br>

All lexical units (words) that pass the syntactic filters are added to the graph and an edge is added between those lexical units, as nodes, that co-occur within a window of n words, that create an undirected and unweighted graph is constructed. 

<br>

Next, a score is calculated for each vertex and the PageRank algorithm is applied for many iterations until it converges. Lastly, the vertices are sorted in reverse order of their score and the top T vertices are extracted.

<br>

### Analysis of the Results of Text Rank: 

The text rank algorithm gives results similar to those in the research paper and online implementations for window size = 5 and by applying a syntactic filter to only consider nouns and propositions. 

<br>

Moreover, a larger window decreases the accuracy of the results since all words in the text receive a higher score, while a smaller window fails to capture the importance of side-by-side words in the same context.

<br>

### Review of Text Rank:

Text Rank is efficient for fast and lightweight extraction of keywords. It can be applied on documents, articles, any piece of text to get the underlying keywords of the piece of text representative of the document. 

<br>

It is also completely unsupervised and draws information only from text itself. However, text rank still cannot achieve the same results as that of supervised models, since a limitation is imposed on the number of keywords to be selected, which creates a smaller dataset. 

<br>

Text Rank can be improved by modifying the algorithm to consider the position of the words in a piece of text or by considering a set of documents instead of a single one to extract global information.

<br>

[<strong><u>Website](https://text-rank-website.herokuapp.com/)

<br>

[<strong><u>GitHub](https://github.com/AhaanKanaujia/Keyword-Extraction)