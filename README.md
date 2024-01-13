# Sentiment-Analysis-Fake-News-Detection

In this project, I trained an NLP model that categorizes news text as REAL or FAKE depending on the contents. This was done using the Transformer architecture - I added a softmax classification layer on top of the Transformer encoder layer. The model was trained from scratch and built using PyTorch, and I used Huggingface for word-tokenization. The number of tokens(in any given input) was capped to 512, and the word embeddings reduced the dimensionality of each token from 30522 to 768
