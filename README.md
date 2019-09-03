# Notebooks

Notebooks, data, and models for various projects I've worked on.

Some datasets and models are too large for Github to handle and live on my personal server instead. If you encounter any missing data, that's what's happened!

## Contents

### Emotion Detection v1

I use VGG16 for the lower layers of my model and add a few additional layers to perform emotion classification. Accuracy is only around 45% across 7 classes (random would be 14%).

### Emotion Detection v2

I implement [this paper](https://arxiv.org/pdf/1710.07557.pdf) which uses the same dataset as **Emotion Detection v1** and creates an XCEPTION model. Accuracy is 65%.

### FLYRds

A data science challenge from a startup.

### MNIST Transfer Learning

I create a CNN that classifies clothing. I then apply this model to clothing I found on Google images.
