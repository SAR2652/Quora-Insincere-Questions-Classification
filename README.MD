# Quora Insincere Questions Classification
### Tested Approaches:<br>
**I. Probabilistic Modelling**
1. TF-IDF based Vectorization w/o Lemmatization + Logistic Regression 
2. TF-IDF based Vectorization w/o Lemmatization + Multinomial Naive Bayes Classification
 
**II. Deep Learning**<br>
1. Selected Hyperparameter values for max_features (Number of words learned by Keras Tokenizer) & maxlen (Maximum permissible Length of Sequence).
2. Unpacked GLoVe (**Glo**bal **Ve**ctors for Word Representation) Embeddings for Keras API's Embedding Layer
3. Trained a Recurrent Neural Network using GLoVe Embeddings and obtained an accuracy of **95.62%** during Cross Validation. 
