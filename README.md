# Facial Recognition Using Deep Neural Network

This repository includes jupyter notebooks and test pictures of our project.

We are trying to predict the names of people in a picture provided.  
<img src="https://github.com/skylarhuang/ML_project/blob/master/mg_result.PNG?raw=true">

To do this, we considered a well-known pre-trained Convolutional Deep Neural Networks, called VGG-FACE.

Then we created our own datasets and fine tuned the model.

Our Team Members are:
* Sui Huang: sh4507@nyu.edu
* Bowen Li: bl2305@nyu.edu

## Facial Recognition Using Pre-Trained VGG-Face
#### Jupyter notebook of our project can be found here [pre_trained_vgg_face.ipynb](https://github.com/skylarhuang/ML_project/blob/master/pre_trained_vgg_face.ipynb)

In VGG-Face, the dataset has already be trained and weights can be downloaded [here](http:http://www.robots.ox.ac.uk/~vgg/software/vgg_face/src/vgg_face_matconvnet.tar.gz).

We are building our project according to [this](https://aboveintelligent.com/face-recognition-with-keras-and-opencv-2baf2a83b799) page.
We are using the OpenCV cascade to cut out faces referencing [this](https://realpython.com/blog/python/face-recognition-with-python/)  page.

## Train VGG-Face Architecture Using Our Own Dataset
#### Jupyter notebook of our project can be found here [pre_trained_vgg_face.ipynb](https://github.com/skylarhuang/ML_project/blob/master/Fine_Tuning_Vgg_Face.ipynb).

We created our own dataset with 1496 photos of 10 different celebrities. 
The size of our databset is over 100 files so you can download it from [here](https://drive.google.com/a/nyu.edu/file/d/1hgcajyL_qAPl61nkU1NVft-JNaw6L9Lo/view?usp=sharing).

<img src="https://github.com/skylarhuang/ML_project/blob/master/Dataset.PNG?raw=true">

We are trying to fine tune layer to VGG-Face achitecture refrencing [this](https://blog.keras.io/building-powerful-image-classification-models-using-very-little-data.html) page and [this](https://github.com/rcmalli/keras-vggface) page.

The highest accuracy we have currently is >98%.

### Unfinished, will update soon

## Library Version
python 3.6.1

Anaconda 4.3.30

Tensorflow 1.4.0

Keras 2.0.9

Pillow 4.3.0

OpenCV-python 3.3.0.10

## System Configuration
OS： Windows10

CPU: Intel(R) Core(TM) i7-6700 @ 3.4Ghz(8 CPUs)

GPU：NVIDIA GeForce GTX 1070 
