# Tweets - Cases of violence against women
**Author: Isabella Tannus Correa**

Database containing tweets published at:

* **Case Elaine Caparroz:** between Feb 16, 2009 - Jun 06, 2020

* **Case Eliza Samúdio:** between Oct 13, 2009 - Jun 06, 2020

* **Case Eloá Cristina:** between Oct 13, 2008 - Jun 06, 2020

* **Case Eva Luana:** between Aug 19, 2009 - Jun 06, 2020

* **Case Mariana Ferrer:** between May 20, 2009 - Jun 06, 2020

* **Case Poliana Bagatini:** between Feb 24, 2009 - Jun 06, 2020

* **Case Tatiane Spitzner:** between Jul 22, 2009 - Jun 06, 2020

The database is available in two different formats:

* **cases db (1 and 2):** all of the collected tweets in their original format containing all the metadata (# likes, # RTs, link, etc), without duplicates, without news, the tweets processed, stemmed, data about pre-processing, and topics of LDA, all of this per case. 
* **cases training:** part of the original database per case and per character (aggressor, victim, case) manually labeled by me with sentiment expressed in each tweet (positive, neutral or negative). Theses fields can be used as a training set for supervised classification algorithms.

I used the tool [GetOldTweets](https://github.com/Jefferson-Henrique/GetOldTweets-python) to collect the tweets, and the data collected was classified using Naive Bayes classifier.

You can [read it](https://bellatannus.github.io/pesquisas.html) (in Portuguese) and understand how I used the database in my paper.

**If you use any part of this database, please cite the paper!**
