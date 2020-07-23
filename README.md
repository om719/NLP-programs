# NLP-programs

This repository contains a few programs whose core revolves around natural language processing.

1) Word_embedding:-
   A set of Wikipedia text files are used as the dataset(You can use any text file). The data is preprocessed and each line is used as a single document. The term-frequency-inverse-document-frequency is then calculated for the corpus generated. The result of this tfidf multi linear array is passed through the TSNE function to reduce it into 3 dimensions. This represents the word_embeddings. Analogies can then be generated
   
2) Text_Classification:-
   A csv file is used as the dataset where a particular line or passage is classified into one of 6 categories. Word2Vec pretrained model is used to represent the words as vectors. The respective X and Y columns are then passed through a logistic regression function to train the model and subsequent predictions can be made.
   
3) Text_Prompt:-
   The brown corpus is used for data. The data is preprocessed and each word is given a number. The vocabulary is restricted to 2000 words. Each sentence is represented in the form of numbers corresponding to their words. A multi linear array containing the bigrams is generated. Using the bigrams we predict the top 5 most probable words given an unfinished sentance.
   
4) Image_classification:-
    A simple CNN is built to classify 4 classes of images. 
