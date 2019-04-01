# CNN-CIFAR10-Classifier

2nd lab in Computer Vision course (CS-4E3) spring semester 2019. This lab is a hands-on Pytorch library in Python besides, it is a direct application on Convolutional Neural Networks (CNN).

## Project Environment
1. Python3
2. Pytorch library
3. Numpy
4. Matplotlib
5. [CIFAR10](https://www.cs.toronto.edu/~kriz/cifar.html)
<br>The CIFAR-10 dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images. 
The classes are completely mutually exclusive. There is no overlap between automobiles and trucks.
<br>Here are the classes in the dataset, as well as 10 random images from each:
![](https://i.ibb.co/dBDz9DV/Screen-Shot-2019-04-01-at-11-12-28-PM.png)
The project is developed in [Google Colaboratory](https://colab.research.google.com/notebooks/welcome.ipynb) environment.

## Project Steps
### Part1: Building a CNN to classify CIFAR10 images
![General CNN Overview](https://i.ibb.co/mbfthdt/Screen-Shot-2019-04-01-at-11-09-26-PM.png)
1. Loading CIFAR10 Dataset
2. Designing a CNN to classify the CIFAR10 photos, we used [this tutorial](https://pytorch.org/tutorials/beginner/blitz/neural_networks_tutorial.html) as a guide.
3. Monitoring accuarcy after changing:  
- Size of kernel
- Number of epochs
4. **BONUS:** Plotting the variations in accuracy after each change

### Part2: Building Incpetion-like CNN using Pytorch to Classify CIFAR10

1. Build Inception v1 with the following architectrue:
![](https://i.ibb.co/Svz2DpV/Screen-Shot-2019-04-01-at-11-23-28-PM.png)
2. Build Inception v2 with the following architecture:
![](https://i.ibb.co/rmbCwPT/Screen-Shot-2019-04-01-at-11-23-52-PM.png)
3. Set desired number of epochs to train *(We chose a small number of epochs due to long training time)*
4. Compare both results from v1 and v2
