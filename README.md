# mnist digit classifier

a cnn built with keras to classify handwritten digits from the mnist dataset. achieves 99.07% test accuracy.

## overview

trains a convolutional neural network to recognize digits 0–9 from 28x28 grayscale images.

## what's in here

- data loading and preprocessing (normalization, one-hot encoding)
- cnn with two conv+pool blocks and a dense head
- training and evaluation
- confusion matrix visualization
- misclassified image inspection

## stack

- python
- tensorflow / keras
- numpy
- matplotlib
- seaborn
- scikit-learn

## usage

```bash
pip install tensorflow numpy matplotlib seaborn scikit-learn
```

then just run the notebook or script. the mnist dataset is loaded automatically via keras.

## accuracy

| model | test accuracy |
|-------|--------------|
| dense network | 97.73% |
| cnn | 99.07% |

## dataset

[mnist](http://yann.lecun.com/exdb/mnist/) — 60,000 training images, 10,000 test images of handwritten digits.
