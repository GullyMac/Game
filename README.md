# StarCraft2 Player Data Analysis

This project is an entry for the 3rd Monthly Data Analysis Competition organized by DACON. (2nd Winner)

> 3-person Team Project\
> Period : 20.03.01 ~ 20.04.15 (about 1.5months)\
> Subject : Binary Classification\
> Role : Data Preprocessing, Source code customizing

DACON main : https://newfront.dacon.io/

Competition Info. : https://dacon.io/competitions/official/235583/overview/

Source Code : https://github.com/GullyMac/Game/blob/master/game_code.ipynb

Report : https://github.com/GullyMac/Game/blob/master/game_report.pdf

20.08.20 last edit

---

## 0. Environment

* Language : Python
* Editor : Google Colaboratory (Jupyter Notebook)

   ! Performance can change depending on the hardware allocated by Colab.
   
* CPU : Intel® Xeon®
* RAM : about 25GB
* Disk : about 68GB
* GPU : Tesla P100

   ! When using GPU, there are a little of differences in result.

---

## 1. Introduction

#### Background:

Games and data analytics competitions have a similar context in that they compete on digital information.

This tournament predicts the winner or loser based on the action data of StarCraft 2 matches.

The algorithms we create can further improve player's gaming skills.

#### Organizer: KORAIA, DACON

#### Metric: AUC

---

## 2. Data Set

#### Data Sets are provided by DACON

#### Response Variable

* winner

#### Explanatory Variable
* various variables derived from game_id, time, playaer, species, event, event_contents

---

## 3. Library

#### Environment Setting

* google.colab.drive : mount at google drive
* warnings : ignore warning message
* os : directory setting

#### Data Manipulation

* pandas : data manipulation
* numpy : matrix operation
* random : random number generation
* time : time measurement
* re : use regular expressions

#### Visualization

* matplotlib.pyplot : graph drawing

#### Modeling

* sklearn.model_selection.train_test_split : seperate train and validation data set
* sklearn.model_selection.KFold : k-fold cross validation
* sklearn.metrics : residual measurement
* bayes_opt : Bayesian optimization
* functools.partial : freeze function’s arguments
* catboost : CatBoost modeling
* lightgbm : lightGBM modeling

