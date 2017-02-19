# Getting and Cleaning Data: Project Assignment
## Introduction
The orgininal data that was used to for the following data analysis can be found here: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

In order to be able to reproduce the commands contained in __*run_analysis.R*__, the working directory must contain the unzipped data in a folder named "UCI HAR Dataset". The unzipping defaults to this folder name.

The folder should contain two subfolders, "train" and "test" as well as four text files: README.TXT, features_info.txt, features.txt and activity_labels.txt.

The content of the files are described in the Codebook.md in this repository.

## The raw files
In summary, the following files are used in the analysis:

_**X_train.txt:**_ The activity measures that are captured by the smartphone

_**subject_train.txt:**_ The list of individuals that correspond to the activity

_**y_train.txt:**_ The type of activity of the individual during the measurement


The same holds for the test set files: _**X_test.txt**_, _**subject_test.txt**_ and _**y_train.txt**_


_**features.txt:**_ The list of activity measures i.e. the variable names

_**activity_labels.txt:**_ A list of possible types of activities.



## Nr. of observations

test data:  2'947

train data: 7'352 


## Data Analysis
1. The code in *run_analysis.R* includes comments on each individual step.
2. In summary, the code reads the train and the test set with the activity measures.
3. In a next step, the information on the individual and on the specific activity is assigned to the measurement.
4. As the activity is coded from 1-5, we convert the variable to factors with meaningful labels.
5. Next, the train and test set is merged and only variables containing information on mean and standard deviation measures are kept.
6. Additionally, special characters and upper case letters are removed from the variable names to ensure R standards.
7. As a last step, we compute the average per individual and activity for all measures and write this tidy data set to the disk (__*data_averages.txt*__).

