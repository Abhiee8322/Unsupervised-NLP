# Unsupervised-NLP
## Performed NLP on textual data and classified into clusters using unsupervised learning


Text is everywhere in the form of opinions, complaints, news and information; each of us are contributing in general to put text throughout the internet. The large amount of text which is present in the unstructured format can be used for welfare of the society and businesses by analysing the sentiments and trends. A part of NLP deals with Text processing and analysis.

Commonly available text can not be directly used for analysis, it needs to pre-processed first, and that is where NLTK, the most popular library for text processing in Python, comes into the picture.<br/>

In this project I have performed unsupervized learning on the given textual data. Following are the steps taken:<br/>

Imported neccessary libraries.<br/>
Load the data<br/>
Basic inspection of the data.<br/>
Text cleaning(Removed punctuation, whitespaces, lowercase the text).<br/>
Text Pre-Processing(Removed stopwords, tokenisation, lemmatization)<br/>
Copying the cleaned data into a variable<br/>
Data vizualization<br/>
Plotted Word-cloud<br/>
Plotted most occuring words/log-log plot.<br/>
Converted the words into vector using TF-IDF vectorizer.<br/>
Graph of summary of silhoutte score obtained from the clustering models.<br/>
Kmeans clustering.<br/>
Checking the number of clusters using elbow method and silhoutte graph.<br/>
Model validation and generating cluster labels.<br/>
Summary of data points in different clusters.<br/>
retrieving data based upon cluster made.<br/>
Cluster labelling.<br/>
DBSCAN model and its optimization<br/>
Birch model<br/>
