### Image Caption Generator Using Deep Learning

#### Project Overview:
The goal of this project is to generate descriptive captions for a given image. The dataset includes 8,000 images, each paired with 5 different captions. To achieve this, features are extracted from both the images and the corresponding text captions. These features are then combined to predict the next word in the caption sequence. A Convolutional Neural Network (CNN) is employed for extracting image features, while a Long Short-Term Memory (LSTM) network is used for processing the text. The model's performance is evaluated using the BLEU Score.

#### Dataset:
- Download link: [Flickr8k Dataset](https://www.kaggle.com/adityajn105/flickr8k)

#### Environment:
- Platform: Kaggle

#### Libraries:
- NumPy
- Matplotlib
- Keras
- TensorFlow
- NLTK
