# Inverted Index
It is a data structure that stores mapping from words to documents or set of documents i.e. directs you from word to document. 

Or in other words:
- For each term t, we must store a list of documents that contains t.
- Identify each document by a *docID*, a document serial number

## Contstruction of Inverted Index 
1. Fetch all documents and gather the words from each document
2. Process each word (e.g. convert to lowercase)
3. Check for each word, if it is present then add reference of document to index else create new entry in index for that word.
4. Repeat above steps for all documents and sort the words.

## Initial stages of text processing
* Convert plural to singular
  - apples to apple
* Convert to lowercase
  - Castle to castle
* Tokenization
  - Cut character sequence into word tokens
    - Deal with "John's", a-state-of-art-solution
* Normalization
  - Map text and query term to same form
    - You want U.S.A and USA to match
* Stemming
  - We may wish different forms of a root to match
    - authorize, authorization
* Stop words
  - We may omit very common words (or not)
    - the, a, to, of
  
