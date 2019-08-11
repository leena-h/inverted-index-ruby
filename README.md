# Inverted Index
It is a data structure that stores mapping from words to documents or set of documents i.e. directs you from word to document. 

Or in other words:
- For each term t, we must store a list of documents that contains t.
- Identify each document by a *docID*, a document serial number

## Contstruction of Inverted Index 
1. Fetch all documents and gather the words from each document
3. Modify each word to be lowercase and singular
3. Check for each word, if it is present then add reference of document to index else create new entry in index for that word.
4. Repeat above steps for all documents and sort the words.
