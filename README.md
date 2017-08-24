# Semantic-Analytics-using-NLP-on-Amazon-Review-Dataset

## Objective 

To build a project which could scrape reviews from the web. Perform sentiment analysis by identifying positive and negative reviews. Feed these reviews to a DBN and SVM to classify the reviews.


## Approach

- To scrape amazon reviews from the web using Rvest
- Apply the sentiment analysis to the reviews using positive and negative dictionary from the lexicon libraries
- Vectorize the documents into vectors using Text2Vec
- Build DBN and SVM models

## Semantic Analysis

They deal with the understanding of data under various logical clusters/meanings rather than preset categories of positive or negative (or neutral or conflict). It comprises of extracting relevant meanings from the given piece of information by realting words.



## Algorithms used 

-SVM
-DBN


## STEPS: 

◦	Packageused:  Text2Vec
◦	Created mapping between term to term called Document-Term matrix (DTM).
◦	Used create vocabulary from text2Vec to create the Vocab.
◦	Used the tokenized data and Vocab to create DTM
◦	Used TfIdf function to create the vector represnation of the Text.
◦	Output from Text2Vec: 1728*2905

