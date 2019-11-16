# My First assignment Score
[0.03449655043925795, 0.9919]

## 1. Convolution
The process of doing element wise multiplication with the kernel(feature extractor) and the part of image(typically size of kernel), followed by summing of those values to get a single value is called convolution.

## 2. Filters/Kernels
Filters/kernels are  matrix/group of weights used to extract features  from the input image. These are used to detect edges and gradients,textures,patterns,parts of objects as well as objects.

## 3. Epochs
Epoch means, one time all the images(batch may contain all images or some images) in the training set went through all the layers to get the required result

## 4. 1x1 Convolution
This convolution generally useful to filter the good channels out of many channels available, it can be used to increase channels too but in special cases

## 5. 3x3 Convolution
Primary kernel or feature extractor used to convolve on top of images/channels to get the result.Each kernel will have it's own 
purpose like extracting the particular type of edge,feature etc.

## 6. Feature Maps
Collection of channels containing similar features, in which each channel contains the same type of features which are generated by the kernel.

## 7. Activation Function
The function which will fire the required values in the process of forward propogation.

## 8. Receptive Field
The number of pixel values which can be seen from each resultant value of the convolution in feature map/channel to the previous layer or input image is called Receptive Field.

There are two types of receptive fields one is local receptive field and the other is global receptive field.

Local receptive field means the receptive field value of each value in the feature map/channel of one convolution layer will be calculated with respect to the previous convolution layer only.

Global receptive field means the receptive field value of each value in the feature map/channel of one convolution layer will be calculated with respect to the all the remaining convolution layers till the input image.
