# Lip Reading

This is a specifically developed lip reading model which recognizes spoken words and sentences only from visual lip movements captured in video sequences.

This model is made in google colaboratory and it leverages the power of convolutional neural networks (CNNs) and recurrent neural networks (RNNs) to extract temporal and spatial features from lip regions, enabling it to decode speech information solely from lip movements.

# Dataset:
GRID Corpus(2006)
the corpus consists of high-quality audio and video (facial) recordings of 1000 sentences spoken by each of 34 talkers (18 male, 16 female), for a total of 34000 sentences. Sentences are of the form "put red at G9 now".
Out of these we took the data from speaker number 1,2,3,4,5,6,7,10,11 and 20.

# Pre-processing:
We encoded the extracted alignments so that it becomes easier to handle the vocabulary data. We used the VGG16 pre-trained model to extract facial features from the captured videoframes.

# Results:
This dataset gives 66.46% accuracy on the used data.
