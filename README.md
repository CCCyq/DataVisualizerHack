# DataVisualizerHack

My hack at #HackIllinois

Motivation - to help users better understand reviews when they make a search.

Summary - Worked on analyzing reviews from the yelp dataset, performing keyword extraction, sentiment analysis and generating a word cloud for beter summarization/visualization of the reviews. The system's generic capability will allow it to be used with any dataset.

Steps -
- You can download the dataset at http://www.yelp.com/dataset_challenge
- Set up and run Elasticsearch.
- Process the dataset and index the required data.
- Helper scripts to perform various tasks like - process data, load data from dataset, keyword extraction and sentiment analysis, split data for elasticsearch bulk processing, searchapi and flask server.
- For UI used bootstrap

External APIs used
- Alchemy API for advanced text analysis.
- Bootstrap for UI.
- Flask to serve requests in a RESTful way.
- ElasticSearch for indexing and searching. 
- NLTK for language modelling

Output is in the form of a word cloud

- Sample output for Timpone's.

![](https://raw.githubusercontent.com/moontails/DataVisualizerHack/master/images/cloud_large.jpg)
