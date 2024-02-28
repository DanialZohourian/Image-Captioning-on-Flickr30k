# Image-Captioning-on-Flickr30k
I implemented four distinct models for an Image Captioning task on the Flickr30k dataset. The evaluation metrics used are BLEU and ROUGE scores, which we will talk about later. All of the models followed the same approach: a pre-trained CNN (ResNet 50) for image feature extraction and an RNN for caption generation. In the first model (Vanilla), a simple RNN was used. In the second model (LSTM), the simple RNN was turned into an LSTM. In the third model (Attention), Attention mechanism was added and finally in the fourth method (GloVe), pre-trained word embeddings were implemented. 

The full documentation can be seen in document.pdf
