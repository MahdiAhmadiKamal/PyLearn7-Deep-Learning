# Transfer Learning
Transfer learning is a machine learning technique in which knowledge gained through one task or dataset is used to improve model performance on another related task and/or different dataset. In other words, transfer learning uses what has been learned in one setting to improve generalization in another setting.


<img src="pics/transfer learning.jpg" width="600">

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
```
jupyter nbconvert --to script 5_animals_classification_tl.ipynb
```
### Results
Comparing the results after employing Transfer Learning 

|  |  Train  | Validation |  Train_TL  | Validation_TL |
| --------------- | --------------- | --------------- | --------------- | --------------- |
| Loss | 0.062 | 1.206 | 0.008 | 0.036 |
| Accuracy | 0.972 | 0.755 | 0.998 | 0.998 |

<img src="5 animals classification\outputs\image.png" width="600">


## 17 flowers classification 🌻🌼🌷
### How to Run
Execute this command in terminal:
```
jupyter nbconvert --to script 17_flowers_classification_augment.ipynb
```
```
jupyter nbconvert --to script 17_flowers_classification_augment_tl.ipynb
```
### Results
Comparing the results after employing Transfer Learning 

|  |  Train  | Validation | Test |  Train_TL  | Validation_TL | Test_TL |
| ---------- | ---------- | ---------- | ---------- | ---------- |---------- | ---------- |
| Loss | 0.53 | 0.92 | 1.12 | 0.04 | 0.34 | 0.27 |
| Accuracy | 0.82 | 0.73 | 0.72 | 0.99 | 0.87 | 0.91 |

<img src="17 flowers classification\outputs\image.png" width="600">


## 7-7 faces classification 🧔🏻👩🏻‍🦳👨🏻👨🏽‍🦳👩🏻‍🦱

### How to Run
Execute this command in terminal:
```
jupyter nbconvert --to script face_recognition.ipynb
```
```
jupyter nbconvert --to script face_recognition_inference.ipynb
```
### Results
#### with dropout
<img src="7-7 faces classification\outputs\acc_loss_dropout.png" width="600">

|  |  Train  | Validation |
| --------------- | --------------- | --------------- |
| Loss | 0.007 | 0.429 |
| Accuracy | 1.000 | 0.863 |

#### without dropout
<img src="7-7 faces classification\outputs\acc_loss.png" width="600">

|  |  Train  | Validation |
| --------------- | --------------- | --------------- |
| Loss | 0.004 | 0.381 |
| Accuracy | 1.000 | 0.901 |

<img src="7-7 faces classification\outputs\cm.png" width="450">

## fellow and clergyman
### How to Run
Execute this command in terminal:
```
jupyter nbconvert --to script fellow_and_clergyman.ipynb
```
```
jupyter nbconvert --to script fellow_and_clergyman_inference.ipynb
```
```
jupyter nbconvert --to script fellow_and_clergyman_bot.ipynb
```

### Results

|  |  Train  | Validation |
| --------------- | --------------- | --------------- |
| Loss | 0.016 | 0.332 |
| Accuracy | 0.992 | 0.933 |

<img src="fellow and clergyman\outputs\cm.png" width="450">


## Python
This program is written using [Python](https://www.python.org/) language and the following tools:

<img src="pics/tensorflow.png" width="170">
<img src="pics/scikit-learn.png" width="170">
<img src="pics/numpy.png" width="170">
<img src="pics/matplotlib.png" width="170">