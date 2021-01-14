# Amherst-History

I worked with a peer in STAT-495 Advanced Data Analysis (taken in fall 2020) to analyze the text found in [History of Amherst College During Its First Half Century, 1821-1871](https://archive.org/details/historyofamherst00tyleiala/page/14/mode/2up) by William Seymour Tyler.

We shared our findings in a pdf report titled ["Amherst History Report"](https://github.com/nfrontero20/amherst-history/blob/master/report/report.pdf) (the Rmd can be found [here](https://github.com/nfrontero20/amherst-history/blob/master/report/report.Rmd)).

Some highlights from the report include: 

  - Data wrangling:
    - Wrote a function that imports all 29 text files (one for each chapter), cleans them, and returns a dataframe
    - The dataframe contains a row for every chapter that contains both the chapter number and a string of all the text within the chapter
  - Analysis: 
    - Identified top 10 most frequent words throughout the entire book, and most frequent word for each chapter
    - Identified the top tf-idf [(term frequency-inverse document frequencies)](https://en.wikipedia.org/wiki/Tf%E2%80%93idf) for each chapter
    - Created a word cloud for the entire book and for a particular chapter
