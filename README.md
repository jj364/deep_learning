# deep_learning
Repository for playing around with modern methods in Deep Learning

## GAN - Generative Adversarial Network
Contains one notebook, keras_GAN, used for learning the basics of GANs using google colab

## null_class
Testing whether the addition of a 'null' class of randomly generated data when training can serve to regularise a network when training.  
Only tested on MNIST so far and had some issues with EarlyStopping but the null class did appear to add a small benefit

TODO - Test on other datasets CIFAR10, CIFAR100, EMNIST for example

## fuzzyClasses
Notebook fuzzy_mnist testing fuzzy class labels for the mnist dataset

Doesn't really seem to be giving good results at all - which I suppose isn't surprising given that onehot encoding with a defined class label works so well.
I just thought this would be fun to try out. Still very much working on this! 

## Handwriting
Contains one handwriting.ipynb notebook using CNNs to classify letters from the extended mnist (emnist) set

I looked at adding a class for spaces between letters to classify strings of letters in words

Really didn't get very far with this - hope to come back to it one day
