Bank-Note-Authentication-Artificial-Neural-Network-Tensorflow-Model-Adam-Optimizer
An Artificial Neural Network Model using Tensorflow and Adam Optimizer, it can identify whether a note is a real note or a fake one.

Data Set Information:
https://archive.ics.uci.edu/ml/datasets/banknote+authentication

Data were extracted from images that were taken from genuine and forged banknote-like specimens. For digitization, an industrial camera usually used for print inspection was used. The final images have 400x 400 pixels. Due to the object lens and distance to the investigated object gray-scale pictures with a resolution of about 660 dpi were gained. Wavelet Transform tool were used to extract features from images.

Attribute Information:
variance of Wavelet Transformed image (continuous)
skewness of Wavelet Transformed image (continuous)
curtosis of Wavelet Transformed image (continuous)
entropy of image (continuous)
class (integer)
Using Tensorflow created a deep neural network or artificial neural network for creating and saving the model(checkpoint). The python code file "Detecting_fake_bank_notes.ipynb" contains comments that are easy to understand what every function does. Uses one hot encoding for the labeled output of the dataset.

I have created a multilayer perceptron with 2 hidden layer and 4 neurons each layer that uses Adam optimizer to minimize the cost with 100 epochs.
