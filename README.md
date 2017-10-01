# Word2Vec
Word2vec word-vector embeddings are a representation of words into a n- dimensional (usually 300-D) vector hyperplane. Algorithms like n-grams are used to recognize the context in which a word comes. The algorithm chunks out group of n words from the sentence and then it tries to predict the neighbourhood words of the word under consideration. A shallow neural network gets trained through the loss gradually.
In this project, our own model of word2vec is trained to understand the context of Game of Thrones by giving it the data from the 5 text books of Game of Thrones. Each word in vocabulary is converted into 300-D vectors, 
T-SNE library is used to squash these vectors into 2-D plots. Clusters of characters of Game of thrones, clusters of food items can easily be seen in the plot.

https://www.youtube.com/watch?v=pY9EwZ02sXU
