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

- DataCamp offers further smaller courses on pandas and data structuring
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
We learn about data transformation and working with specific data types in pandas: string, missing, categorical and temporal.

#### Required reading

- PDA: chapter 7 and sections 11.1-11.2, 12.1, 12.3.
- PML: chapter 4, section 'Handling categorical data'.

#### Inspirational reading
- Lohr, Steve. 2014. "[For Big-Data Scientists, ‘Janitor Work’ Is Key Hurdle to Insights](https://www.nytimes.com/2014/08/18/technology/for-big-data-scientists-hurdle-to-insights-is-janitor-work.html)"



## Session 5: Data structuring 2

We round-off data structuring by learning two powerful tools in data structuring: combining different data sets and the-split-apply-combine framework which is called `groupby` in pandas.

#### Required reading
- PDA: chapters 8 and 10 and sections 5.3, 6.1-6.2
- Wickham, Hadley. 2011. “[The Split-Apply-Combine Strategy for Data Analysis](http://www.jstatsoft.org/article/view/v040i01)”. Journal of Statistical Software 40(1).



## Session 6: Scraping 1 - Introduction to web scaping

We learn to create and collect datasets from the web. This means interacting with apis and webpages and extracting information from unstructured webpages.

#### Required readings

- Chapter 2: "Working with Web Data and APIs." in **[Big Data and Social Science: A Practical Guide to Methods and Tools](http://www.bigdatasocialscience.com/home)** edited by Ian Foster, Rayid Ghani, Ron S. Jarmin, Frauke Kreuter, and Julia Lane.(This can be found under session_6 in teaching material on github).

- Shiab, Nael. 2015. "[On the Ethics of Web Scraping and Data Journalism](http://gijn.org/2015/08/12/on-the-ethics-of-web-scraping-and-data-journalism/)". Global Investigative Journalism Network.

#### Inspirational reading

Below are some interesting academic papers using data scraped from online sources that might provide inspiration for your exam project.

- Stephens-Davidowitz, Seth. 2014. "[The cost of racial animus on a black candidate: Evidence using Google search data](http://www.sciencedirect.com/science/article/pii/S0047272714000929)." *Journal of Public Economics*, 118: 26-40.

- Stephens-Davidowitz, Seth, Hal Varian, and Michael D. Smith. 2016. "[Super Returns to Super Bowl Ads?](http://people.ischool.berkeley.edu/~hal/Papers/2015/super.pdf)". R & R, *Journal of Political Economy*.

- Stephens-Davidowitz, Seth, and Hal Varian. 2015 "[A Hands-on Guide to Google Data](https://www.aeaweb.org/aea/2016conference/program/retrieve.php?pdfid=772)." Google working paper.

- Barberá, Pablo. 2015. "[Birds of the same feather tweet together: Bayesian ideal point estimation using Twitter data](http://pan.oxfordjournals.org/content/23/1/76.short)." *Political Analysis*, 23.1: 76-91.

- Cavallo, A. (2018). ["Scraped data and sticky prices"](https://www.mitpressjournals.org/doi/abs/10.1162/REST_a_00652). *Review of Economics and Statistics*, 100(1).

- Bond, Robert M., et al. 2012. "[A 61-million-person experiment in social influence and political mobilization](http://www.ncbi.nlm.nih.gov/pmc/articles/PMC3834737/)." *Nature*, 489.7415: 295-298.


## Session 7: Scraping 2 - Parsing
Here we develop our skills in parsing. This is a fundamental data science skill that goes beyond web scraping alone.

#### Required readings
- Chapter 2. Dan Jurafsky and James H. Martin: [Speech and Language Processing (3rd ed. draft)] (https://web.stanford.edu/~jurafsky/slp3/)
- Introduction to pattern matching using regex: "[An introduction to regex in python](https://scotch.io/tutorials/an-introduction-to-regex-in-python). Blog.


## Session 8: Advanced Scrapers
We become good scrapers being able to automate browsing and using regex but to become great we need to study what others are doing to avoid being scraped. This includes bots, honey traps, AJAX, etc.

#### Inspirational reading
- [Most Commonly used techniques to Prevent Scraping:](https://medium.com/@betoayesa/using-the-content-as-an-anti-scrape-weapon-draft-9bb10cd30e5c)
- [Advanced Web Scraping Tactics](https://www.pluralsight.com/guides/advanced-web-scraping-tactics-python-playbook)
- [Scraping Sites That Use JavaScript and AJAX](https://oup-arc.com/protected/files/content/file/1505319833942-CH9---Scraping-Sites-that-Use-JavaScript-and-AJAX.pdf)
- [Facebook Scraper 2020: How to Scrape Facebook Group with Python](https://www.bestproxyreviews.com/facebook-scraper/)


## Session 9: Ethics and Big Data Intro

TBD

## Session 10: Modeling and machine learning

We introduce basic machine learning (ML) concepts. We start with the simple machine learning models for classification problems.

#### Required readings

- PML: chapters 1,2 and the following section from chapter 3:
  - Modeling class probabilities via logistic regression

## Session 11: Regression and regularization

We explain the overfitting problem of modelling. We show one possible solution is regularization of standard linear models.

#### Required readings

- PML: chapter 3, the following sections:
  - Tackling overfitting via regularization
  - Partitioning a dataset into separate training and test sets
- PML: chapter 4, the following sections:
  - Bringing features onto the same scale
  - Selecting meaningful features
- PML: chapter 10, the following sections:
    - Introducing linear regression
    - Implementing an ordinary least squares linear regression model
    - Evaluating the performance of linear regression models
    - Using regularized methods for regression
    - Turning a linear regression model into a curve – polynomial regression




## Session 12: Model selection and cross-validation

We introduce cross validation to gauge overfitting and review the linear model.

#### Required readings

- PML: chapter 6.


## Session 13: Non-linear ML and applications

We give an overview of non-linear machine learning models and outline how machine learning tools can be applied in social science.

#### Required readings

- Mullainathan, Sendhil, and Jann Spiess. 2017. ["Machine Learning: An Applied Econometric Approach."](https://www.aeaweb.org/articles?id=10.1257/jep.31.2.87) *Journal of Economic Perspectives*, 31 (2): 87-106.

- Varian, Hal. 2012 [Big Data: New Tricks for Econometrics](http://people.ischool.berkeley.edu/~hal/Papers/2013/ml.pdf)

- Athey, Susan. 2018. [The Impact of Machine Learning on Economics](http://www.nber.org/chapters/c14009.pdf) *NBER*




## Session 14: Text data
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
