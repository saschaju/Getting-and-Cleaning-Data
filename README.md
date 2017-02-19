# Getting and Cleaning Data: Project Assignment
## Introduction
The orgininal data that was used to for the following data analysis can be found here: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

In order to be able to reproduce the commands contained in "run_analysis.R", the working directory must contain the unzipped data in a folder named "UCI HAR Dataset". The unzipping defaults to this folder name.

The folder should contain to subfolders, "train" and "test" as well as four text files: README.TXT, features_info.txt, features.txt and activity_labels.txt.

The content of the files are described in the Codebook.md in this repository.

## The raw files
In summary, the following files are used in the analysis:

_**X_train.txt:**_ The activity measures that are captured by the smartphone

_**subject_train.txt:**_ The list of individuals that correspond to the activity

_**y_train.txt:**_ The type of activity of the individual during the measurement

The same holds for the test set files: _X_test.txt_, _subject_test.txt_ and _y_train.txt_



**nr. of observations**

test data:  2'947

train data: 7'352 


_**features.txt:**_ The list of activity measures i.e. the variable names

_**activity_labels.txt:**_ A list of possible types of activities.

## Data Analysis


