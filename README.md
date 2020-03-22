# StarCraft2 Player Data Analysis

This project is an entry for the 13th BigData Competition organized by DACON.

DACON main : https://newfront.dacon.io/

Competition Info. : https://dacon.io/competitions/official/235583/overview/

Report : https://github.com/GullyMac/game/blob/master/game.ipynb

---

## 0. Introduction

---

## 1. Data Set

##### Data Sets are provided by DACON

#### Response Variable : winner

#### Explanatory Variable : various variables derived from game_id, time, playaer, species, event, event_contents

---

## 2. Library

#### Environment Setting

google.colab.drive
warnings
os

#### Data Manipulation

pandas : 데이터 조작, 분석
numpy : 행렬 연산
random : 난수 생성
time :시간 측정

#### Modeling

sklearn.model_selection.train_test_split : train, validation 분리
sklearn.metrics : 잔차 측정
catboost : CatBoost 모델링

#### Visualization

matplotlib.pyplot : 그래프 생성
