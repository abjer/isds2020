---
title: Course readings
date: 2020-06-27
markup: mmark
---


Textbook for general introduction to social data science:  
- **[Big by Bit - Social research in the digital age](https://www.bitbybitbook.com/)** by Matthew J. Salganik **[BBB]**, free online version [here](https://www.bitbybitbook.com/en/1st-ed/preface/).

Textbooks for data science in Python   
- **[Python for Data Analysis, 2nd ed.](http://wesmckinney.com/pages/book.html)** (2017) by Wes McKinney **[PDA]**
- **[Python Machine Learning, 2nd ed.](https://www.packtpub.com/big-data-and-business-intelligence/python-machine-learning-second-edition)** (2017) by Sebastian Raschka & Vahid Mirjalili **[PML]**


## Preparation and Assignment 0

The course begin with your preparation for the teaching. This consists in Assignment 0 which is a learning module and assignment together. In terms of teaching it provides  an overview of basic Python and how to use it for data analysis. We also introduce markdown for writing text that allows simple formatting in plain text.

#### Required reading

- DataCamp 2016, ‘Jupyter tutorial’, available [here](https://www.datacamp.com/community/tutorials/tutorial-jupyter-notebook)
- PDA: sections 1.1-1.3, 4.1, 5.1-5.2 as well chapters 2-3.
- Nolan, John. 2015. "[How to Write Faster, Better & Longer: The Ultimate Guide to Markdown](https://blog.ghost.org/markdown/)."

#### Inspirational reading and other sources for learning

There are many good resources for learning how to master data structuring. See below for two ways of self-learning:

- DataCamp offers further smaller courses on Pandas and data structuring
- Rada, Greg. 2013. "[Intro to pandas data structures](http://www.gregreda.com/2013/10/26/intro-to-pandas-data-structures/)"- read all three sections.


## Session 1a & 1b: Introduction to the course and Python

We introduce the course and provide an overview of logistics. We also introduce git and GitHub that we are wokring with.

#### Required readings

**Introduction to Social Data Science**
- BBB: chapter 1

- Grimmer, Justin. ["We are all social scientists now: how big data, machine learning, and causal inference work together."](https://web.stanford.edu/~jgrimmer/bd_2.pdf) *PS: Political Science & Politics* 48.1 (2015): 80-83.


**Git - a tool for storing and sharing code**
- Jones, Zachery. 2015. "[Git & Github tutorial](http://zmjones.com/git-github-tutorial/)".

#### Inspirational reading

If you’re interested, and want to delve deeper into coding and programming (it's optional!), we highly recommend the following posts:

- [The Scientist: Get With the Program](http://www.the-scientist.com/?articles.view/articleNo/43632/title/Get-With-the-Program/)
- [Why learn Python](https://www.continuum.io/why-python)
- [Economist on the Rise of Python](https://www.economist.com/science-and-technology/2018/07/21/python-has-brought-computer-programming-to-a-vast-new-audience)
- [What is Code?](http://www.bloomberg.com/graphics/2015-paul-ford-what-is-code/?cmpid=twtr1)

A broad, early, and easy-to-read idea of data driven (social) science:

- Anderson, Chris. 2008. "[The end of theory: The data deluge makes the scientific method obsolete](https://www.wired.com/2008/06/pb-theory/)." *Wired*, 16-07.

## Session 2: Strings, queries and APIs

We start to leverage our python knowledge to make queries on the web. This allows us to pull data directly from Statistics Denmark's API.

#### Required reading
- PDA: sections 2.3 pp. 39-43, 3.3, 6.1 pp. 178-180, 6.3 and 7.3 pp. 211-213
- Gazarov, Petr. 2016. "[What is an API? In English, please.](https://medium.freecodecamp.org/what-is-an-api-in-english-please-b880a3214a82)"



## Session 3: Intro to visualization

We introduce visualizations in Python. We use [pandas](http://pandas.pydata.org/pandas-docs/stable/) and [seaborn](https://seaborn.pydata.org/index.html). Both these modules are built on the fundamental and flexible plotting module [matplotlib](https://matplotlib.org).

#### Required reading
- PDA: chapter 9
- Christ Moffitt, 2017. ["Effectively Using Matplotlib"](http://pbpython.com/effective-matplotlib.html)
- Read sections 1-3 in: Wickham, Hadley. 2010. "[A Layered Grammar of Graphics](http://byrneslab.net/classes/biol607/readings/wickham_layered-grammar.pdf)". *Journal of Computational and Graphical Statistics*, Volume 19, Number 1, Pages 3–28.


#### Inspirational reading

- Schwabish, Jonathan A. 2014. "[An Economist's Guide to Visualizing Data](https://www.aeaweb.org/articles.php?doi=10.1257/jep.28.1.209)". *Journal of Economic Perspectives*, 28(1): 209-34.
- Healy, Kieran and James Moody. 2014. "[Data Visualization in Sociology](http://kieranhealy.org/files/papers/data-visualization.pdf)". *Annual Review of Sociology*, 40:105–128.
- Cherdarchuk, Joey. 2013. "[Data Looks Better Naked](https://www.darkhorseanalytics.com/blog/data-looks-better-naked/)", blog post.


## Sessions 4: Data structuring 1
We learn about missing data, data transformation.  

#### Required reading

- PDA: chapter 7 and sections 5.3, 6.1-6.2


#### Inspirational reading
- Lohr, Steve. 2014. "[For Big-Data Scientists, ‘Janitor Work’ Is Key Hurdle to Insights](https://www.nytimes.com/2014/08/18/technology/for-big-data-scientists-hurdle-to-insights-is-janitor-work.html)"



## Session 5: Data structuring 2

We learn about categorical data and temporal data. We round-off data structuring by learning two powerful tools in data structuring: combining different data sets and the-split-apply-combine framework which is called `groupby` in pandas.

#### Required reading
- PDA: chapters 8 and 10 and sections 11.1-11.2, 12.1.
- PML: chapter 4, section 'Handling categorical data'.
- Wickham, Hadley. 2011. “[The Split-Apply-Combine Strategy for Data Analysis](http://www.jstatsoft.org/article/view/v040i01)”. Journal of Statistical Software 40(1).

## Session 6: Scraping 1

TBD

## Session 7: Scraping 2

TBD

## Session 7: Scraping 3

TBD

## Session 9: Ethics and Big Data Intro

TBD

## Session 10: Machine learning intro

TBD
## Session 11: Supervised learning 1

TBD

## Session 12: Supervised learning 2

TBD

## Session 13: Supervised learning 3

TBD

## Session 14: Text data
TBD



## Session 15: Text data
We introduce the concept of **Text as Data**, and apply our newly acquired knowledge of supervised learning to a text classification problem.

#### Required readings

- PML: following sections from chapter 8:
  - Preparing the IMDb movie review data for text processing
  - Introducing the bag-of-words model
  - Training a logistic regression model for document classification

- Gentzkow, M., Kelly, B.T. and Taddy, M., 2019. ["Text as data"](https://doi.org/10.1257/jel.20181020) *Journal of Economic Literature* 57(3).

Jurafsky, D., & Martin, J. H. (2019). Vector Semantics and Embeddings. Speech and Language Processing, 3rd ed. draft. https://web.stanford.edu/~jurafsky/slp3/6.pdf


#### Inspirational readings

Gorrell, Genevieve et al. “Twits, Twats and Twaddle: Trends in Online Abuse towards UK Politicians.” ICWSM (2018). https://gate-socmedia.group.shef.ac.uk/wp-content/uploads/2019/07/Gorrell-Greenwood.pdf

Pang, Bo et al. “Thumbs up? Sentiment Classification using Machine Learning Techniques.” EMNLP (2002). https://www.aclweb.org/anthology/W02-1011.pdf
