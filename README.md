# Smart_Movie_Review_Analyser

Objective: To build a movie review analysis system that classifies reviews and provides insights.

This is divided in 3 parts:

Part A: Text Classification & Word Embeddings

       1. Dataset and Classification:
       
          >I used the IMDB review dataset - https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews/data?select=IMDB+Dataset.csv
          >Build a text classifier to predict if reviews are positive or negative
          >Used a simple approach: TF-IDF + Logistic Regression
          
       2. Word Embeddings
       
          >Used pre-trained GloVe embeddings
          >Created document embeddings by averaging word vectors
          >Found similar movies based on review content
          >Visualized top 100 words using t-SNE plot
          
Part B: Neural Networks

       3. ANN Implementation
       
          >Build a 3-layer neural network using TensorFlow/Keras
          >Gave Input: Review text (as embeddings)
          >Output: Positive/Negative classification
          >Used dropout for regularization
          
      4. CNN for Text
      
          >Implemented a simple 1D CNN for text classification
          >Used convolutional layers to capture local patterns in text
          >Compared performance with ANN
          
Part C: Text Summarization

      5. Review Summarization
      
         >Implemented extractive summarization using TextRank
         >Summarized long reviews into 2-3 sentences
         >Tested on reviews with 200+ words
