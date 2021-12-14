# Unsupervised-NLP
## Performed NLP on textual data and classified into clusters using unsupervised learning


#Text is everywhere in the form of opinions, complaints, news and information; each of us are contributing in general to put text throughout the internet. The large amount of text #which is present in the unstructured format can be used for welfare of the society and businesses by analysing the sentiments and trends. A part of NLP deals with Text processing #and analysis.

#Commonly available text can not be directly used for analysis, it needs to pre-processed first, and that is where NLTK, the most popular library for text processing in Python, #comes into the picture.

#In this project I have performed unsupervized learning on the given textual data. Following are the steps taken:

#Imported neccessary libraries.
#Load the data
Basic inspection of the data.
Text cleaning(Removed punctuation, whitespaces, lowercase the text).
Text Pre-Processing(Removed stopwords, tokenisation, lemmatization)
Copying the cleaned data into a variable
Data vizualization
Plotted Word-cloud
Plotted most occuring words/log-log plot.
Converted the words into vector using TF-IDF vectorizer.
Graph of summary of silhoutte score obtained from the clustering models.
Kmeans clustering.
Checking the number of clusters using elbow method and silhoutte graph.
Model validation and generating cluster labels.
Summary of data points in different clusters.
retrieving data based upon cluster made.
Cluster labelling.
DBSCAN model and its optimization
Birch model
