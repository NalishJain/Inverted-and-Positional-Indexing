## Assignment

This repo involves implementing text preprocessing, inverted index with boolean queries, and positional index with phrase queries on a dataset of text files.

**Folder Structure**:

text_files/: This folder contains the dataset of text files.
out_files/: This folder will store the preprocessed versions of the text files.

Implementation Details:
Data Preprocessing (Q1):

Lowercase the text, perform tokenization, remove stopwords, punctuations, and blank space tokens from each text file in the dataset.
The preprocessed files are saved in the preprocessed_data/ folder.
Unigram Inverted Index and Boolean Queries (Q2):

Create a unigram inverted index from scratch without using any library.
Save and load the unigram inverted index using Python's pickle module.
Implement support for boolean queries (AND, OR, AND NOT, OR NOT) and generalized queries.
Preprocess the input sequence before executing the queries.
Positional Index and Phrase Queries (Q3):

Create a positional index from scratch without using any library.
Save and load the positional index using Python's pickle module.
Implement support for phrase queries.
Preprocess the input sequence before executing the queries.

