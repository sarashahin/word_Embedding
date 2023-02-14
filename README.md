# word_Embedding

There are two ways to obtain word embeddings:

Learn word embeddings jointly with the main task you care about (e.g. document classification or sentiment prediction). In this setup, you would start with random word vectors, then learn your word vectors in the same way that you learn the weights of a neural network. Load into your model word embeddings that were pre-computed using a different machine learning task than the one you are trying to solve. These are called pre-trained word embeddings.
