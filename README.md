The aim of this project is to develop a recommendation system that suggests related authors to users based on their research interests. The system achieves this by scraping the descriptions of research papers of all authors and performing topic modeling using LDA and BERTopic algorithms. By clustering the papers into different topics, the system identifies authors with similar research interests. The resulting clusters are then visualized using data visualization techniques to help users explore the distribution of topics and identify related authors. The recommendation system takes in the name of an author and suggests other authors with similar research interests based on the topics and keywords in their research papers.

NLP Concepts Used:
Bert
LDA
Topic Modeling

Packages and Techniques used:
pyLDAvis
NLTK
matplotlib
gensim
spacy
CoherenceModel
ldamodel
sentence_transformers
BERTopic
umap
