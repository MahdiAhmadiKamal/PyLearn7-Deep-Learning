# Face Recognition
The present project recognizes the faces of a number of Iranian characters using [DeepFace](https://github.com/serengil/deepface). DeepFace is a lightweight face recognition and facial attribute analysis framework for python, is utilized.

<img src="pics/deepface-icon-labeled.png" width="200">

## Description
In this project a function named generate_dataset is being developed to convert images to feature vectors using deepface package. After the dataset is ready, a Multi-Layer Perceptron (MLP) neural network model is implemented and trained on the dataset. Finally, face_recognition function is written which can predict new images using the trained model.

## How to Install
Run following command:
```
pip install -r requirements.txt
```

## How to Run
Execute this command in terminal:
```
jupyter nbconvert --to script face_recognition.ipynb
```

## Results

<img src="pics\output.png" width="450">

|   |  train data  | test data |
| --------------- | --------------- | --------------- |
| Accuracy | 0.93 | 0.83 |
| Loss | 0.25 | 0.81 |


## Python
This program is written using [Python](https://www.python.org/) language and the following tools:

<img src="pics/numpy.png" width="170">

<img src="pics/matplotlib.png" width="170">

<img src="pics/pandas.png" width="170">

<img src="pics/scikit-learn.png" width="170">