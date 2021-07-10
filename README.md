<img src="https://user-images.githubusercontent.com/58368119/125155558-76313f80-e17e-11eb-9d98-9ee88d672758.png" width="90%"></img> 

# Classify This Movie
In-Class Prediction Competition on Kaggle


**Problem Statement**

For movie lovers, the movie poster makes up the first impression about the movie contents and its genre.
Humans can grasp the cues like color, expressions on the faces of actors etc to quickly determine the genre (horror, comedy, animation etc) of a movie. Though it might seem simple, it involves millions of concurrent processes occurring in a less than a jiffy! If humans are able to inherently predict genre of a movie by a glance at its poster, can't we expect the same from a machine ?

It has been studied that the human brain tends to make intuitions based on the color characteristics, local texture based features and structural cues of posters. Hence, the posters possess some characteristics which could be utilized for genre classification

In this competition, your goal is to predict the genres of movies from their posters.


**About competition, Dataset and leader board please go to below link**

[https://www.kaggle.com/c/cl-cv2020](https://www.kaggle.com/c/cl-cv2020)

## Things I Tried:

* Pretrained Models Used:
  1. Resnet-18 
  2. Resnet-50 (0.896-0.921)
  3. Resnext (0.902-0.930)

* Tried different Image Augmentations

* Used FastAI library which is completely build on pytorch and provide easy to understand and implement codes.

## Things to try in Future:

* Train for more epochs
* Ensembling
* Hyper-parameter optimisation
* Fine tuning of different models used

