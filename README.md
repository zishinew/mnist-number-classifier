# mnist digit classifier

a simple neural network built with keras to classify handwritten digits from the mnist dataset

## overview

trains a fully connected neural network to recognize digits 0–9 from 28x28 grayscale images

## what's in here

- data loading and preprocessing (normalization, one-hot encoding)
- fully connected neural network with keras
- training and evaluation
- confusion matrix visualization
- misclassified image inspection

## stack

- python
- tensorflow / keras
- numpy
- matplotlib

## usage

```bash
pip install tensorflow numpy matplotlib
```

then just run the notebook or script. the mnist dataset is loaded automatically via keras

## dataset

[mnist](http://yann.lecun.com/exdb/mnist/) — 60,000 training images, 10,000 test images of handwritten digits.
