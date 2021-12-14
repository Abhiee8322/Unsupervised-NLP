# Unsupervised-NLP
## Performed NLP on textual data and classified into clusters using unsupervised learning


Text is everywhere in the form of opinions, complaints, news and information; each of us are contributing in general to put text throughout the internet. The large amount of text which is present in the unstructured format can be used for welfare of the society and businesses by analysing the sentiments and trends. A part of NLP deals with Text processing and analysis.

Commonly available text can not be directly used for analysis, it needs to pre-processed first, and that is where NLTK, the most popular library for text processing in Python, comes into the picture.<br/>

In this project I have performed unsupervized learning on the given textual data. Following are the steps taken:<br/>

Imported neccessary libraries.<br/>
1. Load the data<br/>
2. Basic inspection of the data.<br/>
3. Text cleaning(Removed punctuation, whitespaces, lowercase the text).<br/>
4. Text Pre-Processing(Removed stopwords, tokenisation, lemmatization)<br/>
5. Copying the cleaned data into a variable<br/>
6. Data vizualization<br/>
7. Plotted Word-cloud<br/>
8. Plotted most occuring words/log-log plot.<br/>
9. Converted the words into vector using TF-IDF vectorizer.<br/>
10. Graph of summary of silhoutte score obtained from the clustering models.<br/>
11. Kmeans clustering.<br/>
12. Checking the number of clusters using elbow method and silhoutte graph.<br/>
13. Model validation and generating cluster labels.<br/>
14. Summary of data points in different clusters.<br/>
15. retrieving data based upon cluster made.<br/>
16. Cluster labelling.<br/>
17. DBSCAN model and its optimization<br/>
18. Birch model<br/>
