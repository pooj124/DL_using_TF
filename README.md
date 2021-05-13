# DL_using_TF
The projects in this repo are a part of my course from UDACITY.This project is a part of my course " Introduction to TensorFlow for Deep Learning" on UDACITY : https://classroom.udacity.com/courses/ud187
I used google colab to work on this, you can implement it on google colab otherwise on Jupyter notbook as well. Through google colab I can directly import my code to the Github.


1. Simple Neural Network : Celsius to Farenheit
2. Image Classification - Fashion MNIST

**The First Project is  a simple neural network to convert celsius values to Farenheit**

You can check out my blog on the same project for a more detailed understanding : https://pooj124.hashnode.dev/simple-neural-network-celsius-to-fahrenheit-ckol3o5sa04op3js1gf2l70oa
This project is a very basic neural network and anyone starting off or wants to understand the overview of if will benefit from this.



**The second Project is Based on classification of clothing**

this dataset is a part of the tensorflow datasets. It's a fashion MNIST dataset that has 10 different types of clothing.
We need to classify an image and see which category of clothing it comes under. For this we create a neural network with a hidden layer by using SparseCategoricalCrossEntropy as the loss function and the adam optimizer. 
For the hidden layer we use Relu and Softmax to determine the probability of the category that the clothing fits under.
