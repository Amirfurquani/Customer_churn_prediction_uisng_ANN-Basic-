# MNIST Digit Classification using ANN

A basic ANN model for classifying handwritten digits from the MNIST dataset.

### Dataset

* 60,000 training and 10,000 test images
* Image size: 28×28 grayscale
* 10 classes (0–9)

### Model

```text
Flatten → Dense(128, ReLU) → Dense(10, Softmax)
```

### Technologies

Python, TensorFlow, Keras, NumPy, Matplotlib, Scikit-learn

### Loss

`sparse_categorical_crossentropy`

### Optimizer

`Adam`
