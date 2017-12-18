# Facial Recognition Using Deep Neural Network

This repository includes jupyter notebooks and test pictures of our project.
We are trying to predict the names of people in a picture provided.  
To do this, we considered a well-known pre-trained Convolutional Deep Neural Networks, called VGG-FACE.  

Our Team Members are:
* Sui Huang: sh4507@nyu.edu
* Bowen Li: bl2305@nyu.edu

## Facial Recognition Using Pre-Trained VGG-Face
In VGG-Face, the dataset has already be trained and weights can be downloaded [here](http:http://www.robots.ox.ac.uk/~vgg/software/vgg_face/src/vgg_face_matconvnet.tar.gz).

Jupyter notebook of our project is [pre_trained_vgg_face.ipynb](https://github.com/skylarhuang/ML_project/blob/master/pre_trained_vgg_face.ipynb)

We are using the OpenCV cascade to cut out faces refrencing [this](https://realpython.com/blog/python/face-recognition-with-python/) page.

## Train VGG-Face architecture using our own dataset
## Not Finish Yet Would Update Soon

We created our own dataset with 500 photos of 10 different celebrities. 
The size of our databset is over 185MB so you can download it from [here](https://drive.google.com/a/nyu.edu/file/d/1WQZAe42fYvGBMItPw79QOP1BdUyxGGd3/view?usp=sharing).

Use [this](https://github.com/skylarhuang/ML_project/blob/master/create_test.ipynb) file to split all photos into two set. Test set will contain 10 photos of each 10 celebrities. And the left will be kept in training set.

We are trying to edit layer to VGG-Face achitecture refrencing [this](https://blog.keras.io/building-powerful-image-classification-models-using-very-little-data.html)page.

## Library Version
python 3.6.1

Anaconda 4.3.30

Tensorflow 1.4.0

Keras 2.0.9

Pillow 4.3.0

OpenCV-python 3.3.0.10
