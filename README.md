# This repository is for 7PAM2002-0509-Data Science Project

The title of the project is Multimodal Movie Genre Prediction.

There are single-model implementations that use either visual posters, trailers, or synopses to predict movie genres, not all together. 

This project aim to use multiple features in a neural multiple models approach to achieve more accurate movie genre recommendations. 
This project focuses on using different types of transformer models to extract features and using a Classifier to predict the genres.

Features:
 - Visual feature (movie posters),
 - Textual feature (movie synopses)

Models:
 - ViT model for Visual feature,
 - BERT model for Textual feature,
 - SVC classifier - to combine both different feature and foe prediction

* About the hierarchy of thie repository:*

- There are two notebooks used for this project, one is for pre-processing and other is for training the model.
- Both the notebooks are found under: /src/notebook
- From the Analysis of source data while pre-processing, images are saved and stored under /images
