Getting and Cleaning Data Peer Assesment Project Codebook
#########################################################

## About the Raw Data
The raw data used is this project was collect by Smartlab - Non Linear Complex Systems Laboratory. More information can be found [here](http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones) and can be downloade [here](https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip)

# Study Design

Since the raw data used was previously collected, please refer [here](http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones)

# Code Book
## data Data Set
* Subject: An identifier of the subject who carried out the experiment.
* Activity: Its activity label.
* A 66-feature vector with time and frequency domain variables.
  - tBodyAccMeanX: Body accelerometer X-axis over time mean (unit: gravity units "g").
  - tBodyAccMeanY: Body accelerometer Y-axis over time mean (unit: gravity units "g").
  - tBodyAccMeanZ: Body accelerometer Z-axis over time mean (unit: gravity units "g").
  - tBodyAccStdX: Body accelerometer X-axis  over time standard deviation (unit: gravity units "g").
  - tBodyAccStdY: Body accelerometer X-axis  over time standard deviation (unit: gravity units "g").
  - tBodyAccStdZ: Body accelerometer X-axis  over time standard deviation (unit: gravity units "g").
  - tGravityAccMeanX: Gravity accelerometer X-axis over time mean (unit: gravity units "g").
  - tGravityAccMeanY: Gravity accelerometer Y-axis over time mean (unit: gravity units "g").
  - tGravityAccMeanZ: Gravity accelerometer Z-axis over time mean (unit: gravity units "g").
  - tGravityAccStdX: Gravity accelerometer X-axis over time standard deviation (unit: gravity units "g").
  - tGravityAccStdY: Gravity accelerometer Y-axis over time standard deviation (unit: gravity units "g").
  - tGravityAccStdZ: Gravity accelerometer Z-axis over time standard deviation (unit: gravity units "g").
  - tBodyAccJerkMeanX: Body accelerometer jerk X-axis over time mean (unit: gravity units "g").
  - tBodyAccJerkMeanY: Body accelerometer jerk Y-axis over time mean (unit: gravity units "g").
  - tBodyAccJerkMeanZ: Body accelerometer jerk Z-axis over time mean (unit: gravity units "g").
  - tBodyAccJerkStdX: Body accelerometer jerk X-axis over time standard deviation (unit: gravity units "g").
  - tBodyAccJerkStdY: Body accelerometer jerk X-axis over time standard deviation (unit: gravity units "g").
  - tBodyAccJerkStdZ: Body accelerometer jerk X-axis over time standard deviation (unit: gravity units "g").
  - tBodyGyroMeanX: Body gyroscope X-axis over time mean (units: radians/second).
  - tBodyGyroMeanY: Body gyroscope Y-axis over time mean (units: radians/second).
  - tBodyGyroMeanZ: Body gyroscope Z-axis over time mean (units: radians/second).
  - tBodyGyroStdX: Body gyroscope X-axis over time standard deviation (units: radians/second).
  - tBodyGyroStdY: Body gyroscope Y-axis over time standard deviation (units: radians/second).
  - tBodyGyroStdZ: Body gyroscope Z-axis over time standard deviation (units: radians/second).
  - tBodyGyroJerkMeanX: Body gyroscope jerk X-axis over time mean (units: radians/second).
  - tBodyGyroJerkMeanY: Body gyroscope jerk Y-axis over time mean (units: radians/second).
  - tBodyGyroJerkMeanZ: Body gyroscope jerk Z-axis over time mean (units: radians/second).
  - tBodyGyroJerkStdX: Body gyroscope jerk X-axis over time standard deviation (units: radians/second).
  - tBodyGyroJerkStdY: Body gyroscope jerk Y-axis over time standard deviation (units: radians/second).
  - tBodyGyroJerkStdZ: Body gyroscope jerk Z-axis over time standard deviation (units: radians/second).
  - tBodyAccMagMean: Body accelerometer magnitude over time mean (unit: gravity units "g").
  - tBodyAccMagStd: Body accelerometer magnitude over time standard deviation (unit: gravity units "g").
  - tGravityAccMagMean: Gravity accelerometer triaxial magnitude over time mean (unit: gravity units "g").
  - tGravityAccMagStd: Gravity accelerometer triaxial magnitude  over time standard deviation (unit: gravity units "g").
  - tBodyAccJerkMagMean: Body accelerometer jerk triaxial magnitude over time mean (unit: gravity units "g").
  - tBodyAccJerkMagStd: Body accelerometer jerk triaxial magnitude  over time standard deviation (unit: gravity units "g").
  - tBodyGyroMagMean: Body gyroscope triaxial magnitude over time mean (units: radians/second).
  - tBodyGyroMagStd: Body gyroscope triaxial magnitude over time standard deviation (units: radians/second).
  - tBodyGyroJerkMagMean: Body gyroscope jerk triaxial magnitude over time mean (units: radians/second).
  - tBodyGyroJerkMagStd: Body gyroscope jerk triaxial magnitude over time mean (units: radians/second).
  - fBodyAccMeanX: Body accelerometer X-axis frequency mean (unit: gravity units "g").
  - fBodyAccMeanY: Body accelerometer Y-axis frequency mean (unit: gravity units "g").
  - fBodyAccMeanZ: Body accelerometer Z-axis frequency mean (unit: gravity units "g").
  - fBodyAccStdX: Body accelerometer X-axis frequency standard deviation (unit: gravity units "g").
  - fBodyAccStdY: Body accelerometer X-axis frequency standard deviation (unit: gravity units "g").
  - fBodyAccStdZ: Body accelerometer X-axis frequency standard deviation (unit: gravity units "g").
  - fGravityAccMeanX: Gravity accelerometer X-axis frequency mean (unit: gravity units "g").
  - fGravityAccMeanY: Gravity accelerometer Y-axis frequency mean (unit: gravity units "g").
  - fGravityAccMeanZ: Gravity accelerometer Z-axis frequency mean (unit: gravity units "g").
  - fGravityAccStdX: Gravity accelerometer X-axis frequency standard deviation (unit: gravity units "g").
  - fGravityAccStdY: Gravity accelerometer Y-axis frequency standard deviation (unit: gravity units "g").
  - fGravityAccStdZ: Gravity accelerometer Z-axis frequency standard deviation (unit: gravity units "g").
  - fBodyAccJerkMeanX: Body accelerometer jerk X-axis frequency mean (unit: gravity units "g").
  - fBodyAccJerkMeanY: Body accelerometer jerk Y-axis frequency mean (unit: gravity units "g").
  - fBodyAccJerkMeanZ: Body accelerometer jerk Z-axis frequency mean (unit: gravity units "g").
  - fBodyAccJerkStdX: Body accelerometer jerk X-axis over time standard deviation (unit: gravity units "g").
  - fBodyAccJerkStdY: Body accelerometer jerk X-axis over time standard deviation (unit: gravity units "g").
  - fBodyAccJerkStdZ: Body accelerometer jerk X-axis over time standard deviation (unit: gravity units "g").
  - fBodyGyroMeanX: Body gyroscope X-axis frequency mean (units: radians/second).
  - fBodyGyroMeanY: Body gyroscope Y-axis frequency mean (units: radians/second).
  - fBodyGyroMeanZ: Body gyroscope Z-axis frequency mean (units: radians/second).
  - fBodyGyroStdX: Body gyroscope X-axis frequency standard deviation (units: radians/second).
  - fBodyGyroStdY: Body gyroscope Y-axis frequency standard deviation (units: radians/second).
  - fBodyGyroStdZ: Body gyroscope Z-axis frequency standard deviation (units: radians/second).
  - fBodyGyroJerkMeanX: Body gyroscope jerk X-axis frequency mean (units: radians/second).
  - fBodyGyroJerkMeanY: Body gyroscope jerk Y-axis frequency mean (units: radians/second).
  - fBodyGyroJerkMeanZ: Body gyroscope jerk Z-axis frequency mean (units: radians/second).
  - fBodyGyroJerkStdX: Body gyroscope jerk X-axis frequency standard deviation (units: radians/second).
  - fBodyGyroJerkStdY: Body gyroscope jerk Y-axis frequency standard deviation (units: radians/second).
  - fBodyGyroJerkStdZ: Body gyroscope jerk Z-axis frequency standard deviation (units: radians/second).
  - fBodyAccMagMean: Body accelerometer magnitude frequency mean (unit: gravity units "g").
  - fBodyAccMagStd: Body accelerometer magnitude frequency standard deviation (unit: gravity units "g").
  - fGravityAccMagMean: Gravity accelerometer triaxial magnitude frequency mean (unit: gravity units "g").
  - fGravityAccMagStd: Gravity accelerometer triaxial magnitude frequency standard deviation (unit: gravity units "g").
  - fBodyAccJerkMagMean: Body accelerometer jerk triaxial magnitude frequency mean (unit: gravity units "g").
  - fBodyAccJerkMagStd: Body accelerometer jerk triaxial magnitude frequency standard deviation (unit: gravity units "g").
  - fBodyGyroMagMean: Body gyroscope triaxial magnitude frequency mean (units: radians/second).
  - fBodyGyroMagStd: Body gyroscope triaxial magnitude frequency standard deviation (units: radians/second).
  - fBodyGyroJerkMagMean: Body gyroscope jerk triaxial magnitude frequency mean (units: radians/second).
  - fBodyGyroJerkMagStd: Body gyroscope jerk triaxial magnitude frequency mean (units: radians/second).

## vars_avg_groupedby_subject_activity Data Set
* Subject: An identifier of the subject who carried out the experiment.
* Activity: Its activity label.
* A 66-feature vector with time and frequency domain variables average grouped by Subject and Activity.
  - tBodyAccMeanXAvg: Body accelerometer X-axis over time mean average (unit: gravity units "g").
  - tBodyAccMeanYAvg: Body accelerometer Y-axis over time mean average (unit: gravity units "g").
  - tBodyAccMeanZAvg: Body accelerometer Z-axis over time mean average (unit: gravity units "g").
  - tBodyAccStdXAvg: Body accelerometer X-axis  over time standard deviation average (unit: gravity units "g").
  - tBodyAccStdYAvg: Body accelerometer X-axis  over time standard deviation average (unit: gravity units "g").
  - tBodyAccStdZAvg: Body accelerometer X-axis  over time standard deviation average (unit: gravity units "g").
  - tGravityAccMeanXAvg: Gravity accelerometer X-axis over time mean average (unit: gravity units "g").
  - tGravityAccMeanYAvg: Gravity accelerometer Y-axis over time mean average (unit: gravity units "g").
  - tGravityAccMeanZAvg: Gravity accelerometer Z-axis over time mean average (unit: gravity units "g").
  - tGravityAccStdXAvg: Gravity accelerometer X-axis over time standard deviation average (unit: gravity units "g").
  - tGravityAccStdYAvg: Gravity accelerometer Y-axis over time standard deviation average (unit: gravity units "g").
  - tGravityAccStdZAvg: Gravity accelerometer Z-axis over time standard deviation average (unit: gravity units "g").
  - tBodyAccJerkMeanXAvg: Body accelerometer jerk X-axis over time mean average (unit: gravity units "g").
  - tBodyAccJerkMeanYAvg: Body accelerometer jerk Y-axis over time mean average (unit: gravity units "g").
  - tBodyAccJerkMeanZAvg: Body accelerometer jerk Z-axis over time mean average (unit: gravity units "g").
  - tBodyAccJerkStdXAvg: Body accelerometer jerk X-axis over time standard deviation average (unit: gravity units "g").
  - tBodyAccJerkStdYAvg: Body accelerometer jerk X-axis over time standard deviation average (unit: gravity units "g").
  - tBodyAccJerkStdZAvg: Body accelerometer jerk X-axis over time standard deviation average (unit: gravity units "g").
  - tBodyGyroMeanXAvg: Body gyroscope X-axis over time mean average (units: radians/second).
  - tBodyGyroMeanYAvg: Body gyroscope Y-axis over time mean average (units: radians/second).
  - tBodyGyroMeanZAvg: Body gyroscope Z-axis over time mean average (units: radians/second).
  - tBodyGyroStdXAvg: Body gyroscope X-axis  over time standard deviation average (units: radians/second).
  - tBodyGyroStdYAvg: Body gyroscope Y-axis  over time standard deviation average (units: radians/second).
  - tBodyGyroStdZAvg: Body gyroscope Z-axis  over time standard deviation average (units: radians/second).
  - tBodyGyroJerkMeanXAvg: Body gyroscope jerk X-axis over time mean average (units: radians/second).
  - tBodyGyroJerkMeanYAvg: Body gyroscope jerk Y-axis over time mean average (units: radians/second).
  - tBodyGyroJerkMeanZAvg: Body gyroscope jerk Z-axis over time mean average (units: radians/second).
  - tBodyGyroJerkStdXAvg: Body gyroscope jerk X-axis over time standard deviation average (units: radians/second).
  - tBodyGyroJerkStdYAvg: Body gyroscope jerk Y-axis over time standard deviation average (units: radians/second).
  - tBodyGyroJerkStdZAvg: Body gyroscope jerk Z-axis over time standard deviation average (units: radians/second).
  - tBodyAccMagMeanAvg: Body accelerometer magnitude over time mean average (unit: gravity units "g").
  - tBodyAccMagStdAvg: Body accelerometer magnitude  over time standard deviation average (unit: gravity units "g").
  - tGravityAccMagMeanAvg: Gravity accelerometer triaxial magnitude over time mean average (unit: gravity units "g").
  - tGravityAccMagStdAvg: Gravity accelerometer triaxial magnitude  over time standard deviation average (unit: gravity units "g").
  - tBodyAccJerkMagMeanAvg: Body accelerometer jerk triaxial magnitude over time mean average (unit: gravity units "g").
  - tBodyAccJerkMagStdAvg: Body accelerometer jerk triaxial magnitude  over time standard deviation average (unit: gravity units "g").
  - tBodyGyroMagMeanAvg: Body gyroscope triaxial magnitude over time mean average (units: radians/second).
  - tBodyGyroMagStdAvg: Body gyroscope triaxial magnitude over time standard deviation (units: radians/second).
  - tBodyGyroJerkMagMeanAvg: Body gyroscope jerk triaxial magnitude over time mean average (units: radians/second).
  - tBodyGyroJerkMagStdAvg: Body gyroscope jerk triaxial magnitude over time mean average (units: radians/second).
  - fBodyAccMeanXAvg: Body accelerometer X-axis frequency mean average (unit: gravity units "g").
  - fBodyAccMeanYAvg: Body accelerometer Y-axis frequency mean average (unit: gravity units "g").
  - fBodyAccMeanZAvg: Body accelerometer Z-axis frequency mean average (unit: gravity units "g").
  - fBodyAccStdXAvg: Body accelerometer X-axis frequency standard deviation average (unit: gravity units "g").
  - fBodyAccStdYAvg: Body accelerometer X-axis frequency standard deviation average (unit: gravity units "g").
  - fBodyAccStdZAvg: Body accelerometer X-axis frequency standard deviation average (unit: gravity units "g").
  - fGravityAccMeanXAvg: Gravity accelerometer X-axis frequency mean average (unit: gravity units "g").
  - fGravityAccMeanYAvg: Gravity accelerometer Y-axis frequency mean average (unit: gravity units "g").
  - fGravityAccMeanZAvg: Gravity accelerometer Z-axis frequency mean average (unit: gravity units "g").
  - fGravityAccStdXAvg: Gravity accelerometer X-axis frequency standard deviation average (unit: gravity units "g").
  - fGravityAccStdYAvg: Gravity accelerometer Y-axis frequency standard deviation average (unit: gravity units "g").
  - fGravityAccStdZAvg: Gravity accelerometer Z-axis frequency standard deviation average (unit: gravity units "g").
  - fBodyAccJerkMeanXAvg: Body accelerometer jerk X-axis frequency mean average (unit: gravity units "g").
  - fBodyAccJerkMeanYAvg: Body accelerometer jerk Y-axis frequency mean average (unit: gravity units "g").
  - fBodyAccJerkMeanZAvg: Body accelerometer jerk Z-axis frequency mean average (unit: gravity units "g").
  - fBodyAccJerkStdXAvg: Body accelerometer jerk X-axis over time standard deviation average (unit: gravity units "g").
  - fBodyAccJerkStdYAvg: Body accelerometer jerk X-axis over time standard deviation average (unit: gravity units "g").
  - fBodyAccJerkStdZAvg: Body accelerometer jerk X-axis over time standard deviation average (unit: gravity units "g").
  - fBodyGyroMeanXAvg: Body gyroscope X-axis frequency mean average (units: radians/second).
  - fBodyGyroMeanYAvg: Body gyroscope Y-axis frequency mean average (units: radians/second).
  - fBodyGyroMeanZAvg: Body gyroscope Z-axis frequency mean average (units: radians/second).
  - fBodyGyroStdXAvg: Body gyroscope X-axis frequency standard deviation average (units: radians/second).
  - fBodyGyroStdYAvg: Body gyroscope Y-axis frequency standard deviation average (units: radians/second).
  - fBodyGyroStdZAvg: Body gyroscope Z-axis frequency standard deviation average (units: radians/second).
  - fBodyGyroJerkMeanXAvg: Body gyroscope jerk X-axis frequency mean average (units: radians/second).
  - fBodyGyroJerkMeanYAvg: Body gyroscope jerk Y-axis frequency mean average (units: radians/second).
  - fBodyGyroJerkMeanZAvg: Body gyroscope jerk Z-axis frequency mean average (units: radians/second).
  - fBodyGyroJerkStdXAvg: Body gyroscope jerk X-axis frequency standard deviation average (units: radians/second).
  - fBodyGyroJerkStdYAvg: Body gyroscope jerk Y-axis frequency standard deviation average (units: radians/second).
  - fBodyGyroJerkStdZAvg: Body gyroscope jerk Z-axis frequency standard deviation average (units: radians/second).
  - fBodyAccMagMeanAvg: Body accelerometer magnitude frequency mean average (unit: gravity units "g").
  - fBodyAccMagStdAvg: Body accelerometer magnitude frequency standard deviation average (unit: gravity units "g").
  - fGravityAccMagMeanAvg: Gravity accelerometer triaxial magnitude frequency mean average (unit: gravity units "g").
  - fGravityAccMagStdAvg: Gravity accelerometer triaxial magnitude frequency standard deviation average (unit: gravity units "g").
  - fBodyAccJerkMagMeanAvg: Body accelerometer jerk triaxial magnitude frequency mean average (unit: gravity units "g").
  - fBodyAccJerkMagStdAvg: Body accelerometer jerk triaxial magnitude frequency standard deviation average (unit: gravity units "g").
  - fBodyGyroMagMeanAvg: Body gyroscope triaxial magnitude frequency mean average (units: radians/second).
  - fBodyGyroMagStdAvg: Body gyroscope triaxial magnitude frequency standard deviation average (units: radians/second).
  - fBodyGyroJerkMagMeanAvg: Body gyroscope jerk triaxial magnitude frequency mean average (units: radians/second).
  - fBodyGyroJerkMagStdAvg: Body gyroscope jerk triaxial magnitude frequency mean average (units: radians/second).
