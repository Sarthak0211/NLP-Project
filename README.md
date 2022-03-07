# NLP-Project

This repository contains all files related to a Natural Language Processing project. I attempted to create a efficient query system to retreive documents based on a users input. Upon being provided with a few keywords, the system returns the documents with the best match along with a summary.

1) Word Extracter- reads all the documents for the match of a particulalar word. Documents were lemmatized as well.
2) Text Summarization - I used a pretrained BERT model to summarize all the documents to three important sentences
3) Dataframe Creation - I create a dataframe that stores the document name, keywords and summary using the above two files
4) Elasticsearch - I then attempted to create an API using Flask and Elasticsearch to put the system into action
