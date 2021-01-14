# amherst-history

I worked with a peer in STAT-495 Advanced Data Analysis (taken in fall 2020) to analyze the text [History of Amherst College During Its First Half Century, 1821-1871](https://archive.org/details/historyofamherst00tyleiala/page/14/mode/2up) by William Seymour Tyler.

We shared our findings in a pdf report titled ["Amherst History Report"](https://github.com/nfrontero20/amherst-history/blob/master/report/report.pdf) (the Rmd can be found [here](https://github.com/nfrontero20/amherst-history/blob/master/report/report.Rmd)).

## Report highlights 

  - Wrote a function that imports all 29 text files (one for each chapter), cleans them, and returns a dataframe with the entire content of the book, with rows separating chapters
  - Identified top 10 most frequent words throughout the entire book, and most frequent word for each chapter
  - Identified the top tf-idf [(term frequency-inverse document frequencies)](https://en.wikipedia.org/wiki/Tf%E2%80%93idf) for each chapter
  - Created a word cloud for the entire book and for a particular chapter
    
## Overview of findings

  1. The top 10 most frequent words in the book, after "college" and "amherst," included words pertaining to three themes: important college personnel (“dr,” “president,” “trustees”); the student body (“students," “class”); religion (“rev,” short for
reverend, "church")
<p align="center">
  <img src="README-images/word-frequencies-book.png" />
</p>

  2. The top 100 most frequent words in the book center around themes that are still pertinent to Amherst College today, and others that are not, as depicted by a word cloud.  Still pertinent words include “department,” “trustees,” “students,” “dollars,” “fund”.  Meanwhile, words that appear in the word cloud that are less relevant to the present day Amherst experience include “legislature,” “christian,” “revival,” “academy,” and “seminary”.
  <p align="center">
  <img src="README-images/word-cloud-book.png" />
</p>
