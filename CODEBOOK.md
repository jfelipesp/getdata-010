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
  - tBodyAccMeanX: Body accelerometer X-axis over time mean.
  - tBodyAccMeanY: Body accelerometer Y-axis over time mean.
  - tBodyAccMeanZ: Body accelerometer Z-axis over time mean.
  - tBodyAccStdX: Body accelerometer X-axis  over time standard deviation.
  - tBodyAccStdY: Body accelerometer X-axis  over time standard deviation.
  - tBodyAccStdZ: Body accelerometer X-axis  over time standard deviation.
  - tGravityAccMeanX: Gravity accelerometer X-axis over time mean.
  - tGravityAccMeanY: Gravity accelerometer Y-axis over time mean.
  - tGravityAccMeanZ: Gravity accelerometer Z-axis over time mean.
  - tGravityAccStdX: Gravity accelerometer X-axis over time standard deviation.
  - tGravityAccStdY: Gravity accelerometer Y-axis over time standard deviation.
  - tGravityAccStdZ: Gravity accelerometer Z-axis over time standard deviation.
  - tBodyAccJerkMeanX: Body accelerometer jerk X-axis over time mean.
  - tBodyAccJerkMeanY: Body accelerometer jerk Y-axis over time mean.
  - tBodyAccJerkMeanZ: Body accelerometer jerk Z-axis over time mean.
  - tBodyAccJerkStdX: Body accelerometer jerk X-axis over time standard deviation.
  - tBodyAccJerkStdY: Body accelerometer jerk X-axis over time standard deviation.
  - tBodyAccJerkStdZ: Body accelerometer jerk X-axis over time standard deviation.
  - tBodyGyroMeanX: Body gyroscope X-axis over time mean.
  - tBodyGyroMeanY: Body gyroscope Y-axis over time mean.
  - tBodyGyroMeanZ: Body gyroscope Z-axis over time mean.
  - tBodyGyroStdX: Body gyroscope X-axis  over time standard deviation.
  - tBodyGyroStdY: Body gyroscope Y-axis  over time standard deviation.
  - tBodyGyroStdZ: Body gyroscope Z-axis  over time standard deviation.
  - tBodyGyroJerkMeanX: Body gyroscope jerk X-axis over time mean.
  - tBodyGyroJerkMeanY: Body gyroscope jerk Y-axis over time mean.
  - tBodyGyroJerkMeanZ: Body gyroscope jerk Z-axis over time mean.
  - tBodyGyroJerkStdX: Body gyroscope jerk X-axis over time standard deviation.
  - tBodyGyroJerkStdY: Body gyroscope jerk Y-axis over time standard deviation.
  - tBodyGyroJerkStdZ: Body gyroscope jerk Z-axis over time standard deviation.
  - tBodyAccMagMean: Body accelerometer magnitude over time mean.
  - tBodyAccMagStd: Body accelerometer magnitude  over time standard deviation.
  - tGravityAccMagMean: Gravity accelerometer triaxial magnitude over time mean.
  - tGravityAccMagStd: Gravity accelerometer triaxial magnitude  over time standard deviation.
  - tBodyAccJerkMagMean: Body accelerometer jerk triaxial magnitude over time mean.
  - tBodyAccJerkMagStd: Body accelerometer jerk triaxial magnitude  over time standard deviation.
  - tBodyGyroMagMean: Body gyroscope triaxial magnitude over time mean.
  - tBodyGyroMagStd: Body gyroscope triaxial magnitude over time standard deviation.
  - tBodyGyroJerkMagMean: Body gyroscope jerk triaxial magnitude over time mean.
  - tBodyGyroJerkMagStd: Body gyroscope jerk triaxial magnitude over time mean.
  - fBodyAccMeanX: Body accelerometer X-axis frequency mean.
  - fBodyAccMeanY: Body accelerometer Y-axis frequency mean.
  - fBodyAccMeanZ: Body accelerometer Z-axis frequency mean.
  - fBodyAccStdX: Body accelerometer X-axis frequency standard deviation.
  - fBodyAccStdY: Body accelerometer X-axis frequency standard deviation.
  - fBodyAccStdZ: Body accelerometer X-axis frequency standard deviation.
  - fGravityAccMeanX: Gravity accelerometer X-axis frequency mean.
  - fGravityAccMeanY: Gravity accelerometer Y-axis frequency mean.
  - fGravityAccMeanZ: Gravity accelerometer Z-axis frequency mean.
  - fGravityAccStdX: Gravity accelerometer X-axis frequency standard deviation.
  - fGravityAccStdY: Gravity accelerometer Y-axis frequency standard deviation.
  - fGravityAccStdZ: Gravity accelerometer Z-axis frequency standard deviation.
  - fBodyAccJerkMeanX: Body accelerometer jerk X-axis frequency mean.
  - fBodyAccJerkMeanY: Body accelerometer jerk Y-axis frequency mean.
  - fBodyAccJerkMeanZ: Body accelerometer jerk Z-axis frequency mean.
  - fBodyAccJerkStdX: Body accelerometer jerk X-axis over time standard deviation.
  - fBodyAccJerkStdY: Body accelerometer jerk X-axis over time standard deviation.
  - fBodyAccJerkStdZ: Body accelerometer jerk X-axis over time standard deviation.
  - fBodyGyroMeanX: Body gyroscope X-axis frequency mean.
  - fBodyGyroMeanY: Body gyroscope Y-axis frequency mean.
  - fBodyGyroMeanZ: Body gyroscope Z-axis frequency mean.
  - fBodyGyroStdX: Body gyroscope X-axis frequency standard deviation.
  - fBodyGyroStdY: Body gyroscope Y-axis frequency standard deviation.
  - fBodyGyroStdZ: Body gyroscope Z-axis frequency standard deviation.
  - fBodyGyroJerkMeanX: Body gyroscope jerk X-axis frequency mean.
  - fBodyGyroJerkMeanY: Body gyroscope jerk Y-axis frequency mean.
  - fBodyGyroJerkMeanZ: Body gyroscope jerk Z-axis frequency mean.
  - fBodyGyroJerkStdX: Body gyroscope jerk X-axis frequency standard deviation.
  - fBodyGyroJerkStdY: Body gyroscope jerk Y-axis frequency standard deviation.
  - fBodyGyroJerkStdZ: Body gyroscope jerk Z-axis frequency standard deviation.
  - fBodyAccMagMean: Body accelerometer magnitude frequency mean.
  - fBodyAccMagStd: Body accelerometer magnitude frequency standard deviation.
  - fGravityAccMagMean: Gravity accelerometer triaxial magnitude frequency mean.
  - fGravityAccMagStd: Gravity accelerometer triaxial magnitude frequency standard deviation.
  - fBodyAccJerkMagMean: Body accelerometer jerk triaxial magnitude frequency mean.
  - fBodyAccJerkMagStd: Body accelerometer jerk triaxial magnitude frequency standard deviation.
  - fBodyGyroMagMean: Body gyroscope triaxial magnitude frequency mean.
  - fBodyGyroMagStd: Body gyroscope triaxial magnitude frequency standard deviation.
  - fBodyGyroJerkMagMean: Body gyroscope jerk triaxial magnitude frequency mean.
  - fBodyGyroJerkMagStd: Body gyroscope jerk triaxial magnitude frequency mean.

## vars_avg_groupedby_subject_activity Data Set
* Subject: An identifier of the subject who carried out the experiment.
* Activity: Its activity label.
* A 66-feature vector with time and frequency domain variables average grouped by Subject and Activity.
  - tBodyAccMeanXAvg: Body accelerometer X-axis over time mean average.
  - tBodyAccMeanYAvg: Body accelerometer Y-axis over time mean average.
  - tBodyAccMeanZAvg: Body accelerometer Z-axis over time mean average.
  - tBodyAccStdXAvg: Body accelerometer X-axis  over time standard deviation average.
  - tBodyAccStdYAvg: Body accelerometer X-axis  over time standard deviation average.
  - tBodyAccStdZAvg: Body accelerometer X-axis  over time standard deviation average.
  - tGravityAccMeanXAvg: Gravity accelerometer X-axis over time mean average.
  - tGravityAccMeanYAvg: Gravity accelerometer Y-axis over time mean average.
  - tGravityAccMeanZAvg: Gravity accelerometer Z-axis over time mean average.
  - tGravityAccStdXAvg: Gravity accelerometer X-axis over time standard deviation average.
  - tGravityAccStdYAvg: Gravity accelerometer Y-axis over time standard deviation average.
  - tGravityAccStdZAvg: Gravity accelerometer Z-axis over time standard deviation average.
  - tBodyAccJerkMeanXAvg: Body accelerometer jerk X-axis over time mean average.
  - tBodyAccJerkMeanYAvg: Body accelerometer jerk Y-axis over time mean average.
  - tBodyAccJerkMeanZAvg: Body accelerometer jerk Z-axis over time mean average.
  - tBodyAccJerkStdXAvg: Body accelerometer jerk X-axis over time standard deviation average.
  - tBodyAccJerkStdYAvg: Body accelerometer jerk X-axis over time standard deviation average.
  - tBodyAccJerkStdZAvg: Body accelerometer jerk X-axis over time standard deviation average.
  - tBodyGyroMeanXAvg: Body gyroscope X-axis over time mean average.
  - tBodyGyroMeanYAvg: Body gyroscope Y-axis over time mean average.
  - tBodyGyroMeanZAvg: Body gyroscope Z-axis over time mean average.
  - tBodyGyroStdXAvg: Body gyroscope X-axis  over time standard deviation average.
  - tBodyGyroStdYAvg: Body gyroscope Y-axis  over time standard deviation average.
  - tBodyGyroStdZAvg: Body gyroscope Z-axis  over time standard deviation average.
  - tBodyGyroJerkMeanXAvg: Body gyroscope jerk X-axis over time mean average.
  - tBodyGyroJerkMeanYAvg: Body gyroscope jerk Y-axis over time mean average.
  - tBodyGyroJerkMeanZAvg: Body gyroscope jerk Z-axis over time mean average.
  - tBodyGyroJerkStdXAvg: Body gyroscope jerk X-axis over time standard deviation average.
  - tBodyGyroJerkStdYAvg: Body gyroscope jerk Y-axis over time standard deviation average.
  - tBodyGyroJerkStdZAvg: Body gyroscope jerk Z-axis over time standard deviation average.
  - tBodyAccMagMeanAvg: Body accelerometer magnitude over time mean average.
  - tBodyAccMagStdAvg: Body accelerometer magnitude  over time standard deviation average.
  - tGravityAccMagMeanAvg: Gravity accelerometer triaxial magnitude over time mean average.
  - tGravityAccMagStdAvg: Gravity accelerometer triaxial magnitude  over time standard deviation average.
  - tBodyAccJerkMagMeanAvg: Body accelerometer jerk triaxial magnitude over time mean average.
  - tBodyAccJerkMagStdAvg: Body accelerometer jerk triaxial magnitude  over time standard deviation average.
  - tBodyGyroMagMeanAvg: Body gyroscope triaxial magnitude over time mean average.
  - tBodyGyroMagStdAvg: Body gyroscope triaxial magnitude over time standard deviation.
  - tBodyGyroJerkMagMeanAvg: Body gyroscope jerk triaxial magnitude over time mean average.
  - tBodyGyroJerkMagStdAvg: Body gyroscope jerk triaxial magnitude over time mean average.
  - fBodyAccMeanXAvg: Body accelerometer X-axis frequency mean average.
  - fBodyAccMeanYAvg: Body accelerometer Y-axis frequency mean average.
  - fBodyAccMeanZAvg: Body accelerometer Z-axis frequency mean average.
  - fBodyAccStdXAvg: Body accelerometer X-axis frequency standard deviation average.
  - fBodyAccStdYAvg: Body accelerometer X-axis frequency standard deviation average.
  - fBodyAccStdZAvg: Body accelerometer X-axis frequency standard deviation average.
  - fGravityAccMeanXAvg: Gravity accelerometer X-axis frequency mean average.
  - fGravityAccMeanYAvg: Gravity accelerometer Y-axis frequency mean average.
  - fGravityAccMeanZAvg: Gravity accelerometer Z-axis frequency mean average.
  - fGravityAccStdXAvg: Gravity accelerometer X-axis frequency standard deviation average.
  - fGravityAccStdYAvg: Gravity accelerometer Y-axis frequency standard deviation average.
  - fGravityAccStdZAvg: Gravity accelerometer Z-axis frequency standard deviation average.
  - fBodyAccJerkMeanXAvg: Body accelerometer jerk X-axis frequency mean average.
  - fBodyAccJerkMeanYAvg: Body accelerometer jerk Y-axis frequency mean average.
  - fBodyAccJerkMeanZAvg: Body accelerometer jerk Z-axis frequency mean average.
  - fBodyAccJerkStdXAvg: Body accelerometer jerk X-axis over time standard deviation average.
  - fBodyAccJerkStdYAvg: Body accelerometer jerk X-axis over time standard deviation average.
  - fBodyAccJerkStdZAvg: Body accelerometer jerk X-axis over time standard deviation average.
  - fBodyGyroMeanXAvg: Body gyroscope X-axis frequency mean average.
  - fBodyGyroMeanYAvg: Body gyroscope Y-axis frequency mean average.
  - fBodyGyroMeanZAvg: Body gyroscope Z-axis frequency mean average.
  - fBodyGyroStdXAvg: Body gyroscope X-axis frequency standard deviation average.
  - fBodyGyroStdYAvg: Body gyroscope Y-axis frequency standard deviation average.
  - fBodyGyroStdZAvg: Body gyroscope Z-axis frequency standard deviation average.
  - fBodyGyroJerkMeanXAvg: Body gyroscope jerk X-axis frequency mean average.
  - fBodyGyroJerkMeanYAvg: Body gyroscope jerk Y-axis frequency mean average.
  - fBodyGyroJerkMeanZAvg: Body gyroscope jerk Z-axis frequency mean average.
  - fBodyGyroJerkStdXAvg: Body gyroscope jerk X-axis frequency standard deviation average.
  - fBodyGyroJerkStdYAvg: Body gyroscope jerk Y-axis frequency standard deviation average.
  - fBodyGyroJerkStdZAvg: Body gyroscope jerk Z-axis frequency standard deviation average.
  - fBodyAccMagMeanAvg: Body accelerometer magnitude frequency mean average.
  - fBodyAccMagStdAvg: Body accelerometer magnitude frequency standard deviation average.
  - fGravityAccMagMeanAvg: Gravity accelerometer triaxial magnitude frequency mean average.
  - fGravityAccMagStdAvg: Gravity accelerometer triaxial magnitude frequency standard deviation average.
  - fBodyAccJerkMagMeanAvg: Body accelerometer jerk triaxial magnitude frequency mean average.
  - fBodyAccJerkMagStdAvg: Body accelerometer jerk triaxial magnitude frequency standard deviation average.
  - fBodyGyroMagMeanAvg: Body gyroscope triaxial magnitude frequency mean average.
  - fBodyGyroMagStdAvg: Body gyroscope triaxial magnitude frequency standard deviation average.
  - fBodyGyroJerkMagMeanAvg: Body gyroscope jerk triaxial magnitude frequency mean average.
  - fBodyGyroJerkMagStdAvg: Body gyroscope jerk triaxial magnitude frequency mean average.
