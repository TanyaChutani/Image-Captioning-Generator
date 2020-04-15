# ImageCaptionGenerator
Image Captioning Generator Keras

## Data
Dataset used - Flickr 8k Dataset  <br />
 <br />
[Flicker8k_Dataset](https://github.com/jbrownlee/Datasets/releases/download/Flickr8k/Flickr8k_Dataset.zip) <br />
[Flickr8k_text](https://github.com/jbrownlee/Datasets/releases/download/Flickr8k/Flickr8k_text.zip)  <br />
 <br />
Flicker8k_Dataset - Contains 8092 images in jpeg format.  <br />
Flickr8k_text - Each image contains 5 description. <br />

## Model
Built and trained a deep learning model for captioning real world image.
- Used pre-trained InceptionV3 to extract feature from image.
- Used pre-trained word2vec embedding, these were feed into a stacked Bi-directional LSTM layer.
- They both were combined and predicted the next word till the end of caption.
