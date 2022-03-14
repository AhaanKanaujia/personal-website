---
title: Keyword Extraction Models
description: Implemented Google's Page Rank Keyword Extraction Method
author: Ahaan Kanaujia
date: 2022-03-14T02:01:20.997Z
tags:
  - Python
  - Machine Learning
  - NLP
---
### Working of Text Rank:

In Text Rank, a piece of text is tokenized and annotated with part of speech tags – a preprocessing step that is required to enable application of syntactic filters. All lexical units (words) that pass the syntactic filters are added to the graph and an edge is added between those lexical units, as nodes, that co-occur within a window of n words, that create an undirected and unweighted graph is constructed. Next, a score is calculated for each vertex and the PageRank algorithm is applied for many iterations until it converges. Lastly, the vertices are sorted in reverse order of their score and the top T vertices are extracted.

### Analysis of Text Rank:

Text Rank is efficient for fast and lightweight extraction of keywords. It can be applied on documents, articles, and any piece of text to get the underlying keywords of the piece of text that are representative of the document. It is also completely unsupervised and draws information only from text itself. However, text rank still cannot achieve the same results as that of supervised models, since a limitation is imposed on the number of keywords to be selected, which creates a smaller dataset. Text Rank can be improved by modifying the algorithm to consider the position of the words in a piece of text or by considering a set of documents instead of a single one to extract global information.