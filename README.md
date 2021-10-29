# Sarcastic messages analysis
## Context

[Reddit](https://www.reddit.com/) is a social network in which users can participate by uploading all kinds of content, and interact through comments present on each publication. On this site there are different subreddits, which are forums dedicated to a specific topic, such as science, politics, music, and so on. In [Reddit](https://www.reddit.com/) there is a convention that if a user writes a comment that should be interpreted sarcastically, the tag "/s" is written at the end of it to avoid any ambiguity, and determine that the comment should not be taken seriously.

## Sarcastic messages analysis
Using the [Sarcasm on Reddit](https://www.kaggle.com/danofer/sarcasm) and [1 million reddit comments](https://www.kaggle.com/smagnan/1-million-reddit-comments-from-40-subreddits) datasets on this context, the main objectives this project are:
- to discover if there are *patterns* that allow finding sarcastic comments based on its text, and being able to predict the nature of the comments (sarcastic or not).
- to determine how *context-dependent* the sarcasm patterns are. 
- to address one of the main problems of *natural language processing*, which is the interpretation of sarcasm when there are no other paraverbal clues apart from its content.

Along with the objectives already mentioned, the purpose of this project is to answer the following questions:
- Is it possible to predict if a message is sarcastic with its content? What is the best way to predict it?
- Are the sarcasm patterns constant within different domains? Does the topic influence the classification process?
- Do the patterns differ greatly between different domains?

**The main file of the proyect ```Hito3.ipynb``` and its web page ```Hito3.html``` are contained in the ```Sarcastic-messages-analysis > Hito 3``` folder on this repository.**

## About

This project was carried out through different *Hitos*. Each *Hito* accumulates certain progress on the development of the project, such as the study of the datasets used, or the use and improvement of data mining techniques (classification, clustering, etc.).

### Hito 1

Contains the first approach on the study of sarcastic comments. An exploration of text data such as data cleansing, hot words and bag of words, most frequent subreddits, etc. The Data Exploration was made using [RMarkdown](https://rmarkdown.rstudio.com/) and python's [pandas library](https://pandas.pydata.org/).

The main file ```Hito1.Rmd``` and its web page ```Hito1.html``` are contained in the ```Sarcastic-messages-analysis > Hito 1``` folder.

### Hito 2

On *Hito 2* the firsts main questions were formulated, along with the first experiment using data mining methods using python's [scikit-learn library](https://scikit-learn.org/stable/)

The main file ```Hito2.ipynb``` and its web page ```Hito2.html``` are contained in the ```Sarcastic-messages-analysis > Hito 2``` folder.

### Hito 3

This is the latest version of the proyect, which contains all of the experiments using [sentence transformers library](https://github.com/UKPLab/sentence-transformers) and python's [scikit-learn library](https://scikit-learn.org/stable/), along with the final conclusions.

The main file ```Hito3.ipynb``` and its web page ```Hito3.html``` are contained in the ```Sarcastic-messages-analysis > Hito 3``` folder.


## Authors
- **Nicolás García Ríos** - [Nicolas-Francisco](https://github.com/Nicolas-Francisco)
- **José Triviño Álvarez** - [Joxito](https://github.com/Joxito)
- **Javier Lavados Jillbert** - [JavierLavados](https://github.com/JavierLavados)
- **Pablo Gutierrez Idalgo** - [penguinhacker](https://github.com/penguinhacker)
- **Sebastián Salinas Rodríguez** - [Salix07](https://github.com/salistito)

Credits
-------
- **Professors:** Felipe Bravo and Bárbara Poblete

<h3 align="center">
  Computer Sciences Department <br> Faculty of Physical and Mathematical Sciences <br> University of Chile
</h3>
