# Image-captioning model based on Flickr8K dataset

## Objectives:
To build a simple image-captioning model using pre-trained CNN model and LSTM model, based on the Flickr8K dataset. This project is primarily for self-learning purpose, on how to build a deep-learning model using Tensorflow.

Update: Use pre-trained word embeddings (GloVe 100D)

## Dataset Descriptions:
Flickr8K dataset contains 8000 images and their reference captions. Originally, you should download a request form to request for the dataset. However, the official site seems to have been taken down, thus I also include the dataset in this project for downloading. Here is the link to the dataset: https://www.kaggle.com/datasets/adityajn105/flickr8k

## Structure:
build_model: It contains the files for constructing, training and evaluating the deep-learning model.

caption_generator.py: It contains the code to use the built model to generate captions for the images in sample_images.

## Installation Requirement:
In this project, I use python and Tensorflow (Keras) to build the deep-learning model. Please make sure that you have Tensorflow (no need to have GPU version) installed in your computer.

To build the model, you need to further download the GloVe word embeddings via [link](https://nlp.stanford.edu/projects/glove/). Please refer to glove.6B --> 100D.


