# This repository is for 7PAM2002-0509-Data Science Project

The title of the project is Multimodal Movie Genre Prediction.

There are single-model implementations that use either visual posters, trailers, or synopses to predict movie genres, not all together. 

I aim to use multiple features in a neural multimodal approach to achieve more accurate movie genre recommendations. This project focuses on using different neural network multimodal models (CNN, NLP, GRU) that integrates multiple features: 
 - Visual data (movie posters),
 - Numerical data (movie release year, duration, and revenue),
 - Textual data (movie synopses and taglines).

** About the hierarchy of thie repository:**

- There are two notebooks used for this project, one is for pre-processing and other is for training the model.
- Both the notebooks are found under: /src/notebook
- From the Analysis of source data while pre-processing, images are saved and stored under /images
