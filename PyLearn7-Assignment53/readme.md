# Custom Datasets_CNN

This part of the repository demonstrates the result of employing CNN for two classification projects. The datasets being used are animals and flowers datasets to classify 5 animals and 17 flowers, respectively. Data augmentation is utilized in both projects and the effect of data augmentation is investigated in the second one. In addition, a telegram bot is defined which is connected to the trained model and recognizes the picture of the flower that user sends.

## How to Install
Run following command:
```
pip install -r requirements.txt
```

## 5 animals classification 🐱🐶🐘🦒🐼

### How to Run
Execute this command in terminal:
```
jupyter nbconvert --to script 5_animals_classification.ipynb
```

### Results

<img src="outputs\5 animals output 1.png" width="500">
<img src="outputs\5 animals output 2.png" width="500">


|  |  Train  | Validation |
| --------------- | --------------- | --------------- |
| Loss | 0.062 | 1.2 |
| Accuracy | 0.97 | 0.75 |

## 17 flowers classification 🌻🌼🌷

### How to Run
Execute this command in terminal:
```
jupyter nbconvert --to script 17_flowers_classification.ipynb
```
```
jupyter nbconvert --to script 17_flowers_classification_augment.ipynb
```
```
jupyter nbconvert --to script 17_flowers_bot.ipynb
```

### Results

<img src="outputs\17 flowers output 1.png" width="500">
<img src="outputs\17 flowers output 2.png" width="500">


|  |  Train  | Validation | Test |
| --------------- | --------------- | --------------- | --------------- |
| Loss | 0.05 | 2.07 | 2.48 |
| Accuracy | 0.98 | 0.63 | 0.58 |
| Loss aug. | 0.53 | 0.92 | 1.12 |
| Accuracy aug. | 0.82 | 0.73 | 0.72 |

## Python
This program is written using [Python](https://www.python.org/) language and the following tools:

<img src="pics/tensorflow.png" width="170">
<img src="pics/scikit-learn.png" width="170">
<img src="pics/numpy.png" width="170">
<img src="pics/matplotlib.png" width="170">