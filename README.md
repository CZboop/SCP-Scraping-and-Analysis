# SCP Scraping and Analysis

Scraping articles from the SCP Foundation and analysing the results.
Includes all main series SCPs 1-6999 that were available at the time of scraping, as well as a collection of joke SCPs, in a separate file.

Data collected using Python, BeautifulSoup and httplib2, using a limited number of requests per minute.

Analysis currently looks at the basics of each column in the data (eg most common verbs, nouns, adjectives in titles, image captions or titles) as well as a basic look at relationships between some columns, such as tags and rating.

Based on the contents of the SCP Wiki, which can be found [here](https://scp-wiki.wikidot.com/). Many thanks to the authors of and contributors to the original work. Each row contains a link back to the original work. Data available under a CC-BY-SA License in accordance with the license of the works it is based on.

Main series 1-6999 dataset available by itself [here](https://www.kaggle.com/czzzzzzz/scp1to7) for ease of use. Kaggle link also has some more details on the data that forms the set. 
