# Adding Convolutional Neural Network to MLP

This part of the repository demonstrates the result of employing convolutional layers in training multi layer perceptron networks in machine learning frameworks. The datasets being used are Mnist, Fashion Mnist, Cifar 10 and Cifar 100 TensorFlow datasets.


## How to Install
Run following command:
```
pip install -r requirements.txt
```

## How to Run
Execute this command in terminal:
```
jupyter nbconvert --to script (file_name).ipynb
```

## Results

| Dataset |  MLP (Machine Learning)  | CNN + MLP (Deep Learning) |
| --------------- | --------------- | --------------- |
| Mnist | 0.98 | 0.99 |
| Fashion Mnist | 0.88 | 0.89 |
| Cifar 10 | 0.41 | 0.84 |
| Cifar 100 | 0.06 | 0.55 |


## Python
This program is written using [Python](https://www.python.org/) language and the following tools:

<img src="pics/tensorflow.png" width="170">

<img src="pics/matplotlib.png" width="170">