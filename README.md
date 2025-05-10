# ML-Project
Image Caption Generator
The model mimics how humans describe images by combining computer vision and natural language processing. It takes an image as input and produces a coherent caption in natural language.
Model Architecture
CNN Encoder: A pretrained convolutional neural network extracts visual features from the image.

RNN Decoder: A recurrent neural network (e.g., LSTM) receives the encoded features and generates descriptive sentences word-by-word.
How It Works
The final classification layer of the CNN is removed.

The output embedding of the CNN is fed into the RNN.

The model is trained end-to-end on image-caption pairs to maximize the likelihood of generating accurate captions.
 Datasets Used
Flickr8k

Flickr30k

Pascal

SBU

 Evaluation
Evaluated using BLEU scores, a common metric in machine translation.

Human evaluation shows that generated captions are contextually relevant and fluent.
