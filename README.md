# MLP-Fashion-MNIST-Classifier
This model was consructed in my neural networks and deep learning module. The task was to classify the fashion MNIST dataset with a neural networks using PyTorch. The requirement of the model was that the images must be split into patches.
## Architecture
### Stem
28x28 images split into 16 patches of 7x7
### Backbone
Two blocks of two MLPs
### Classifier
Mean feature mapping to 10 outputs using softmax
## Final Model
Cross entropy loss was used to perfect the model. 88% test accuracy
