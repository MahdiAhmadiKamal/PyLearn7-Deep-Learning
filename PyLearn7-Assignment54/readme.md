# Transfer Learning
Transfer learning is a machine learning technique in which knowledge gained through one task or dataset is used to improve model performance on another related task and/or different dataset. In other words, transfer learning uses what has been learned in one setting to improve generalization in another setting.


<img src="pics/transfer learning.jpg" width="600">

## How to Install
Run following command:
```
pip install -r requirements.txt
```

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
<img src="7-7 faces classification\outputs\acc_loss_dropout.png" width="450">

|  |  Train  | Validation |
| --------------- | --------------- | --------------- |
| Loss | 0.007 | 0.429 |
| Accuracy | 1.000 | 0.863 |

#### without dropout
<img src="7-7 faces classification\outputs\acc_loss.png" width="450">

|  |  Train  | Validation |
| --------------- | --------------- | --------------- |
| Loss | 0.004 | 0.381 |
| Accuracy | 1.000 | 0.901 |

<img src="7-7 faces classification\outputs\cm.png" width="225">


## Python
This program is written using [Python](https://www.python.org/) language and the following tools:

<img src="pics/tensorflow.png" width="170">
<img src="pics/scikit-learn.png" width="170">
<img src="pics/numpy.png" width="170">
<img src="pics/matplotlib.png" width="170">