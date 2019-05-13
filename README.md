# Handwritten Digit Reconstruction

In the following notebook we will be analysing the mnist dataset with an autoencoder. 
We will lower the dimensionality of the images and then reconstruct them.

The framework being used for the machine learning is Keras.

The model has the following structure:

```
_________________________________________________________________
Layer (type)                 Output Shape              Param #   
=================================================================
input_2 (InputLayer)         (None, 784)               0         
_________________________________________________________________
dense_3 (Dense)              (None, 32)                25120     
_________________________________________________________________
dense_4 (Dense)              (None, 784)               25872     
=================================================================
Total params: 50,992
Trainable params: 50,992
Non-trainable params: 0
_________________________________________________________________
```
