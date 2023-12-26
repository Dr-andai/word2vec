## Word2Vec project

This project attempts to offer and introduction on the Word2Vec model in NLP.
More theory on the principles of word2vec are readily found in these Medium blogh post
https://towardsdatascience.com/introduction-to-word-embedding-and-word2vec-652d0c2060fa
https://towardsdatascience.com/word2vec-explained-49c52b4ccb71
The code from the .ipynb file has been cloned from https://github.com/ritvikmath/YouTubeVideoCode/blob/main/Word2Vec.ipynb

# Step 1
The introductory part of the code gathers Data from Clinicaltrials.gov
The essence of the project is to run the Word2Vec model on the Brief Description of Behavioural Intervention Trials in HIV.

# Step 2
Once data is extracted, it's prepared for training a Skip-gram model.
After which I try to run the code to visualize the word embeddings.

# Step 3
A section of this code is creating a list of tuples containing word pairs and their cosine similarities, then sorting these tuples based on 
the cosine similarities for the word 'hiv' and displaying the top 10 most similar words to 'hiv'.


###
# The general take
More work, in terms of learning the theory and writing the code is needed, to better come up with a 
word2vec model that helps me understand the implementation of the model given the data fed.
