[![View on Medium](https://img.shields.io/badge/Medium-View%20on%20Medium-red?logo=medium)](https://towardsdatascience.com/how-to-create-an-app-to-classify-dogs-using-fastai-and-streamlit-af3e75f0ee28)  [![View on Streamlit](https://img.shields.io/badge/Streamlit-View%20on%20Streamlit%20app-ff69b4?logo=streamlit)](https://share.streamlit.io/brankopoledic/dog_classifier/main/dog_classifier.py)
# Dog Classifier

This is a simple app to classify dogs using [fastai](https://docs.fast.ai/) and [streamlit](https://www.streamlit.io/). The app is deployed using Streamlit Sharing. Click [here](https://share.streamlit.io/brankopoledic/dog_classifier/main/dog_classifier.py) to view and play with the app.  This project is inspired by Chapter 2 of the book Deep Learning for Coders with fastai & PyTorch.

Find the tutorial on how to create your own dog classifier in [this Medium article](https://towardsdatascience.com/how-to-create-an-app-to-classify-dogs-using-fastai-and-streamlit-af3e75f0ee28).

## Overview
### Dataset
450 different dog images are obtained using [Bing Image Search API](https://www.microsoft.com/en-us/bing/apis/bing-image-search-api). There are 150 images of each type of dog. The non-relevant images are removed. 
### Model
The model was trained to recognize 3 types of dog: Winner, Chihuahua, and Basset Hound using fastai. You can find the details of the training in [train_dog_classifier.ipnb](./train_dog_classifier.ipynb) notebook. The model was saved to [dog.pkl](./dog.pkl).
