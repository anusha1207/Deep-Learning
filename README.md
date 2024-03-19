The following 3 projects are from a class taken at Rice University for Computer Vision using Deep Learning Techniques.                      

Multimodal Image-Text Analysis of Movies:

This project uses the MIMDB dataset for Image classification. The dataset contains data corresponding to ~26,000 movies along with their plots (text) and their 
movie posters (images), and other information such as ratings and genres (categories). Each movie can be labeled with 27 categories of movies. For classification, BERT encodings were used where a pretrained BERT model was "fine-tuned" to its parameters so they adapt to the text in this dataset. As an extension this this proejct, a multimodal model 
that can be potentially trained with both images and text is trained. It combines the outptus of a text model and an image model and concatenates them before 
passing them through a final linear layer.



Generating Text with Recurrent Networks:
This project involves training a model to generate movie plots using RNNs based on two instances:
- uncoditioned text generation 
- conditioned on images (image-captioning)



MSVD Video Captioning System:

Video captioning is a meaningful task which helps in the generation of textual descriptions of contents from videos. This project deploys a sequence- to-sequence
LSTM based Recurrent Neural Network with an encoder-decoder architecture that is trained on video-sentence pairs. This model learns to associate a sequence of
video frames with a sequence of words to generate textual descriptions of the video clip.



