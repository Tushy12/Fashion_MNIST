# Fashion_MNIST
## Deep Learning for Image Classification

### The Challenge

The task is to build an image classifier with Keras and Convolutional Neural Networks for the Fashion MNIST dataset. This data set includes 10 labels of different clothing types with 28 by 28 *grayscale* images. There is a training set of 60,000 images and 10,000 test images.**

    Label	Description
    0	    T-shirt/top
    1	    Trouser
    2	    Pullover
    3	    Dress
    4	    Coat
    5	    Sandal
    6	    Shirt
    7	    Sneaker
    8	    Bag
    9	    Ankle boot
    
### The Model

Using Keras to create a model consisting of at least the following layers(free to experiment):
1. 2D Convolutional Layer, filters=32 and kernel_size=(4,4)
2. Pooling Layer where pool_size = (2,2)
3. Flatten Layer
4. Dense Layer (128 Neurons, but feel free to play around with this value), RELU activation
5. Final Dense Layer of 10 Neurons with a softmax activation

