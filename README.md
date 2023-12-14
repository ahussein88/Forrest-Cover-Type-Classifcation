
![UTA-DataScience-Logo](https://github.com/ahussein88/Forrest-Cover-Type-Classifcation/assets/123412804/589417cb-3255-4c97-bcb5-9a9b5ddd12fd)     ![Screen Shot 2023-12-13 at 2 46 16 AM](https://github.com/ahussein88/Forrest-Cover-Type-Classifcation/assets/123412804/5ec78b1a-a4ac-4814-ab2c-2178fa46529a)


# Forest Cover Type Prediction 

* **Description:** This repository contains an attempt to predict the predominate forest cover type strictly from cartographic variables.
  
"Forest Cover Type Prediction" Kaggle challenge ([Link](https://www.kaggle.com/competitions/forest-cover-type-prediction)). 

## Overview

  * **Challenge:**  The dataset contains 15120 observations which contains that ranges from Elevaiton, Slope, and horizontal_distance_to Roadways.

  * **Approach:** In this project, we want to use a variety of algorithms and classifiers to predict the type of tree cover in a sample area within Roosevelt National Forest of Northern Colorado given various other features about the area, including the soil type, the vertical and horizontal distance to hydrology, the elevation, etc. We will use the following algorithms to make our prediction.

  * **Summary of the performance achieved:** K-NN algorithm classified 92.71% of the of the trees correctly. Our decision tree classified 93.56% of the of the trees correctly  
    
## Summary of Workdone: 
*...


### Data

* Data:
  * Type: CSV File
    * Input: The dataset contains 15120 observations for each observation there is a different column 
    * Input: CSV file of features 
  * Size: 96.64 MB
  * Instances (Train, Test, Validation Split): ..

#### Preprocessing / Clean up

* There are 275 outliers in Slope. The normal range is -18.0 - 45.0. 
There are 414 outliers in Horizontal_Distance_To_Hydrology. The normal range is -720.0 - 1212.0. 
There are 5339 outliers in Vertical_Distance_To_Hydrology. The normal range is -179.0 - 255.0. 
There are 10 outliers in Horizontal_Distance_To_Fire_Points. The normal range is -3554.0 - 7128.0. 

#### Data Visualization


### Problem Formulation

* Define:
  * Input / Output
  * Models
    * Describe the different models you tried and why.
  * Loss, Optimizer, other Hyperparameters.

### Training

* Describe the training:
  * How you trained: software and hardware.
  * How did training take.
  * Training curves (loss vs epoch for test/train).
  * How did you decide to stop training.
  * Any difficulties? How did you resolve them?

### Performance Comparison

* Clearly define the key performance metric(s).
* Show/compare results in one table.
* Show one (or few) visualization(s) of results, for example ROC curves.

### Conclusions

* State any conclusions you can infer from your work. Example: LSTM work better than GRU.

### Future Work

* What would be the next thing that you would try.
* What are some other studies that can be done starting from here.

## How to reproduce results

* In this section, provide instructions at least one of the following:
   * Reproduce your results fully, including training.
   * Apply this package to other data. For example, how to use the model you trained.
   * Use this package to perform their own study.
* Also describe what resources to use for this package, if appropirate. For example, point them to Collab and TPUs.

### Overview of files in repository

...

### Software Setup
...

### Data

..
### Training

..

#### Performance Evaluation

..

## Citations

...





