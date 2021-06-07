# SoC-NLPlay-with-Transformers
## Sentiment Classifier
### Data preprocessing
1. Word Tokenization: splitting sentences into an array of words.
2. Remove punctuations(‘.’, ‘,’, ‘/’, etc.)
3. Remove stop words(a, an, the, that, etc.)
4. Lemmatization
### Feature extraction
#### Frequency based Embedding
1. Count Vector/Bag of word: Create a vocabulary of the words used in the document and store the number of repetitions of a particular word in the document. It discards any information about the order of the words in the data.
2. TF-IDF Vector:The idea is to give importance to words which appear only in a subset of documents and decrease the weight of words which occur frequently in all the documents because they may not carry information relevant to a particular document.Formula:
### Data splitting
Number of train samples: 40000 <br />Number of test samples: 10000
### Models
1. Feed Forward neural neural network
2. RNN
3. LSTM
4. GRU

 
