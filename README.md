# Document-retrieval---ranking
This is an iformatino Retrieval(IR) system based for a collection of documents. The collection is a subset of the data used in the TREC 2011 Microblog retrieval task. Each line contains the id of the message and the actural message.

The results of the system on a set of 49 queris
An example topic could be in the following format:
\<top>
\<num> Number:MB001\</num>
\<tittle> BBC World Service staff cuts \</tittle>
\<querytime>  Tue Feb 08 12:30:27 +0000 2011 \</querytime>
\<querytweettime> 34952194402811904 \</querytweettime>
\<top>

# preprocessing: 
Implement preprocessing functions for tokenization and stopword removal.
The index terms will be all the words left after filtering out punctuation tokens, numbers, stopwords, etc.
Use the Porter stemmer to stem the index words. 

# Indexing:
Build an inverted index, with an entry for each word in the vocabulary.
An example of possible index is presented below.
