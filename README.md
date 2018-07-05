# KittiesOrPuppos
I used a Deep ConvNet to classify images as cats or dogs with 99.1% accuracy. 

In this project the goal was to predict whether an image was a cat or dog using a convolutional neural network. Using both Tensorflow and Keras I was able to harness the power of a 2 layer CNN. 

When constructing my CNN I added 2 max pooling layers as well as a flattening layer. The activation function used in this classifier was. A sigmoid 

I used a training dataset of 4000 color images of dogs and 4000 cats. To ensure a reasonable training time I used images that were 64x64 pixels. 

I compiled my classifier using the Adam optimizer and using binary_crossentropy as my loss function due to the binary nature of the output (cat or dog). For ease of understanding the metric I used in this project was accuracy.

As part of pre-processing the image data I used the ImageDataGenerator function to rescale the images. In order to get somewhat high accuracy I set my model to train for 25 epochs. I need up only running 4 epochs before reaching an accuracy of 99.1% and accepting this measure. 
