# Basic-Web-Seach-Engine-in-python

Implementation of two functions:
1. index(URLs), which – given a list of input URLs in the array– 
–  downloads each web page 
–  strips tags in the resulting HTML
–  preprocesses the text data 

2. search(query), which – given a sequence of query words 
–  computes and stores a sparse bag-of-words representation of each page
–  outputs a ranked list of web pages based on the cosine distance measure between the bag-of-words representations of queries and web pages.
