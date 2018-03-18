Naughty Solution Casper Emde Christensen, Ali Khazendar, Stephan Pedersen, Nicklas Vikke (JEFF)

----------------------------------------------------------------------------------------------------------------------------

Assignment 5 - Bloody Television

Import:
- import csv
- import webget
- import gzip
- import shutil
- from collections import Counter

Dataset for Python:

http://www.imdb.com/interfaces/ (title.basics.tsv.gz) Direct link: https://datasets.imdbws.com/title.basics.tsv.gz

Run the code:
Clone github repo: https://github.com/jeff25n/PythonAssignment5

Start git bash and open Jupyter notebook

Select IMDB-data-spg.-5.ipynb, Question 3 .ipynb, VIRKER-FUCKING.ipynb

Run every code-block (ctrl + enter)


Q1: Which year was the most movies released?

Most common releasedates for movies:
2016:   60578
2017:   59168
2014:   58500
2015:   57264
2013:   54217

Q2: Which year was most series ended?

Most common enddates for series:
2017:    2672
2016:    2007
2015:    1591
2014:    1393
2013:    1381

Q3: WWhich genres has the longest runtime per movies?

Q4: Which genre covers the most movies?

Drama,Short:   84271
Short:   56334
Comedy,Short:   50241
Documentary:   43275
Drama:   30782

Q5: What is the average runtime on adult films?

amound_of_adultmovies = 56027
total_min_adultmovies = 5870587

5870587 / 56027 =  104.78139111499813
