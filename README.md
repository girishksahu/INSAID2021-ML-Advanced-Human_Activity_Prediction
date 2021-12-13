# INSAID2021-ML-Advanced-Human_Activity_Prediction
INSAID 2021 ML Advanced Term Project
# Project Description
## Introduction
Client for this project is a Smartphone Company.

* They want to predict the human activity and draw other insights like signs of fatigue in an individual for fitness monitoring.

* They want to monitor six basic activities: three static postures (standing, sitting, lying) and three dynamic activities (walking, walking downstairs and walking upstairs).

* One of the key measurements in this process is prediction of these six activities.

## Current Scenario
The company has captured data of 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz using the embedded accelerometer and gyroscope of the device. The experiments were video-recorded to label the data manually.

Machine learning can help to study data from sensors which are already present in most smartphones and can be analysed to gain rich insights about the candidates/users.

## Problem Statement
The current process suffers from the following problems:

* The company has collected a large amount of sensor data from smartphones but is not able to use it efficiently.
* This data can be utilized to achieve various goals that can help an individual for better health like activity detection and also monitor signs of fatigue.
* They want to automate the process of predicting the activity and draw other insights by analyzing the smartphone sensor data.

## Project Task
* Dataset contains all the necessary information about the different activities of a person which are captured from different sensors.
* Project task is to build a classification model for predicting the activity type.
## Project Deliverables
* Deliverable: Human Activity Prediction.
* Machine Learning Task: Classification
* Target Variable: activity
* Win Condition: N/A (best possible model)
## Evaluation Metric
* The model evaluation will be based on the Accuracy score.
# Data Description
* The columns contains all the necessary information about the different activities of a person which are captured from different sensors.
* Also included in the dataset is the column activity which has the activity that the person is doing.

The dataset is divided into two parts: Train and Test sets.

## Train Set:
* The train set contains 2887 rows and 563 columns.
* The column activity is the target variable.

## Test Set:
* The test set contains 722 rows and 562 columns.
* The test set doesn’t contain the activity column.
* It needs to be predicted for the test set.

# Dataset Feature Description
The Dataset contains the following columns:

| ID | Feature Name | Description of the feature |
| :-- | :--| :--| 
|01| **rn**   | unique id for the observation                     |
|02| **activity** | The activity that the person is performing               |

Rest all features are sensor data.
