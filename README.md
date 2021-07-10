<img src="https://user-images.githubusercontent.com/58368119/125061081-9c95a300-e0ca-11eb-8c85-5c5648cb18aa.png" width="90%"></img> 

# Age Detection of Indian Actors | Analytics Vidhya 

**Got 0.93068 accuracy on test set which puts this result in 20th position in the competetion.**

**About Problem**

Indian Movie Face database (IMFDB) is a large unconstrained face database consisting of 34512 images of 100 Indian actors collected from more than 100 videos. All the images are manually selected and cropped from the video frames resulting in a high degree of variability interms of scale, pose, expression, illumination, age, resolution, occlusion, and makeup. IMFDB is the first face database that provides a detailed annotation of every image in terms of age, pose, gender, expression and type of occlusion that may help other face related applications.

Data - The dataset is cleaned and formatted to give you a total of 26742 images with 19906 images in train and 6636 images in test.

The task is to predict the age of a person from his or her facial attributes. For simplicity, the problem has been converted to a multiclass problem with classes as Young, Middle and Old.


**About competition, Dataset and leader board please go to below link**

[https://datahack.analyticsvidhya.com/contest/practice-problem-age-detection/#LeaderBoard](https://datahack.analyticsvidhya.com/contest/practice-problem-age-detection/#LeaderBoard)

## Things I Tried:

* Pretrained Models Used:
  1. Resnet-50 (0.680 - 0.708)
  2. Efficient_b0 (0.896-0.921)
  3. Efficient_b3 (0.902-0.930)

* Tried different Image Augmentations:
  both train-time (from Albumentation library) and test-time (from TTA library)

* Tried the Adam and Ranger optimisers along with Stratifeid K-fold Cross-validation technique. Also used learning rate scheduling (used ReduceLROnPlateau)

* Trained each model for 20-50 epochs. Used fine-tuning for Resnet (as it has more parameters than effnet models)

## Things to try in Future:

* Pseudo-labelling
* Different ensembling techniques
* Hyper-parameter optimisations


