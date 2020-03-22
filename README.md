# StarCraft2 Player Data Analysis

This project is an entry for the 13th BigData Competition organized by DACON.

DACON main : https://newfront.dacon.io/

Competition Info. : https://dacon.io/competitions/official/235583/overview/

Report : https://github.com/GullyMac/game/blob/master/game.ipynb

20.01.18 last edit

---

## 0. Introduction

#### Organizer: KORAIA, DACON

#### Background:


Games and data analytics competitions have a similar context in that they compete on digital information.

This tournament predicts the winner or loser based on the action data of StarCraft 2 matches.

The algorithms we create can further improve player's gaming skills.

---

## 1. Data Set

###### Data Sets are provided by DACON

#### Response Variable

* winner

#### Explanatory Variable
* various variables derived from game_id, time, playaer, species, event, event_contents

---

## 2. Library

#### Environment Setting

* google.colab.drive : mount at google drive
* warnings : ignore warning message
* os : directory setting

#### Data Manipulation

* pandas : data manipulation
* numpy : matrix operation
* random : random number generation
* time : time measurement

#### Visualization

* matplotlib.pyplot : graph drawing

#### Modeling

* sklearn.model_selection.train_test_split : seperation of train and validation data set 
* sklearn.metrics : residual measurement
* catboost : CatBoost modeling

---

## 3. Data Preprocessing
