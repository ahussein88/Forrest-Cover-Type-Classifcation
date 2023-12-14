
![UTA-DataScience-Logo](https://github.com/ahussein88/Forrest-Cover-Type-Classifcation/assets/123412804/589417cb-3255-4c97-bcb5-9a9b5ddd12fd)     ![Screen Shot 2023-12-13 at 2 46 16 AM](https://github.com/ahussein88/Forrest-Cover-Type-Classifcation/assets/123412804/5ec78b1a-a4ac-4814-ab2c-2178fa46529a)


# Forest Cover Type Prediction 

* **Description:** This repository contains an attempt to predict the predominate forest cover type strictly from cartographic variables.
  
"Forest Cover Type Prediction" Kaggle challenge ([Link](https://www.kaggle.com/competitions/forest-cover-type-prediction)). 

## Overview

  * **Challenge:**  The goal of this challenge is to predict the type of tree cover in a sample area strictly based on cartographic variable such as elevation, shadow coverage, distance to nearby landmarks (roads etcetera), soil type, and local topography.

  * **Approach:** For this project, I utilized scikit decision tree and the K-Nearest Neighbor classifers. The reason why I decided to use scikit decision tree was because I wanted to use it to compare it to the K-Nearest Neighbor classifier and see which algorithm/classifier would be more effificent.

  * **Summary of the performance achieved:** I iniitaly hypotheized that K-NN would be more efficient but after running the data. K-NN algorithm classifier was accurately predicted 92.71% of the of the trees correctly. Where as the decision tree classified 93.56% of the of the trees correctly.
    
## Summary of Workdone: 


### Data

* Data:
  * Type: CSV Files
    * Input: The dataset contained 15120 observations made from different trees that are randomly sorted. The training dataset only contains the cartographic variables.
    * Output: Create a integer classification for the forest cover type, there was a total of 7 different tree types.
  * Size: 96.64 MB
  * Instances (Train, Test, Validation Split): The training set (15120 observations) contains both features and the Cover_Type. The test set contains only the features. You must predict the Cover_Type for every row in the test set (565892 observations).

#### Preprocessing / Clean up

* There are 275 outliers in Slope. The normal range is -18.0 - 45.0. 
There are 414 outliers in Horizontal_Distance_To_Hydrology. The normal range is -720.0 - 1212.0. 
There are 5339 outliers in Vertical_Distance_To_Hydrology. The normal range is -179.0 - 255.0. 
There are 10 outliers in Horizontal_Distance_To_Fire_Points. The normal range is -3554.0 - 7128.0. 

#### Data Visualization

![Screen Shot 2023-12-14 at 2 06 44 PM 1](https://github.com/ahussein88/Forrest-Cover-Type-Classifcation/assets/123412804/d77d5dfc-34b8-44b7-bc1e-4941bcd1d5de)

![Screen Shot 2023-12-14 at 2 24 33 PM](https://github.com/ahussein88/Forrest-Cover-Type-Classifcation/assets/123412804/5800d9e3-3fbc-4084-922a-796568545fb1)

![Screen Shot 2023-12-14 at 2 25 34 PM](https://github.com/ahussein88/Forrest-Cover-Type-Classifcation/assets/123412804/a4e38d38-f309-40f7-9918-ae3c8064dc27)




### Problem Formulation

* Define: Classifer
  * Input: Dataset from train.csv file
  * Output: Reoccuring features that were found
  * Models: The two classifiers that were used were Scikit Decision Tree and K-NN.
    *  
  * Loss, Optimizer, other Hyperparameters.

### Training

* Describe the training: 
  * How you trained: software and hardware. 
  * How did training take. 
  * Training curves (loss vs epoch for test/train).
  * How did you decide to stop training.
  * Any difficulties? How did you resolve them?

### Performance Comparison

* K-NN algorithm classifier accurately predicted 92.71% of the of the trees correctly.
* The decision tree classifier accurately predicted 93.56% of the of the trees correctly.
 
* Clearly define the key performance metric(s).
* Show/compare results in one table.
* Show one (or few) visualization(s) of results, for example ROC curves.

  

### Conclusions

The 

### Future Work

In the future, I'd like to try different types of classifiers and alogrithms and see how they perform. 


## How to reproduce results

* In this section, provide instructions at least one of the following:
   * Reproduce your results fully, including training.
   * Apply this package to other data. For example, how to use the model you trained.
   * Use this package to perform their own study.
* Also describe what resources to use for this package, if appropirate. For example, point them to Collab and TPUs.

### Overview of files in repository

...

### Software Setup



### Data

..
### Training

..

#### Performance Evaluation

..

## Citations

...





