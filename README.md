This project implements an end to end deep learning model that generates descriptive captions for input images using a Convolutional Neural Network (CNN) and Long Short Term Memory (LSTM) architecture. The model is trained on the Flickr8k dataset, which contains 8,000 images with five captions each.

The CNN (a pre-trained model, VGG16) is used to extract visual features from images, while the LSTM network learns to generate a corresponding textual description based on these features and previously generated words.

The caption generation process involves techniques from Natural Language Processing (NLP), including text preprocessing, tokenization, padding, and sequence modeling. 

The performance of the model is evaluated using the BLEU score which is a standard NLP metric for comparing a machine generated caption with one or more reference captions. BLEU-1 to BLEU-4 scores are used to assess unigram to 4-gram overlaps and help determine the fluency and relevance of generated descriptions.
