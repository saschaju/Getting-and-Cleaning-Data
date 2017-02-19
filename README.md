# Getting and Cleaning Data: Project Assignment
## Introduction
The orgininal data that was used to for the following data analysis can be found here: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

In order to be able to reproduce the commands contained in "run_analysis.R", the working directory must contain the unzipped data in a folder named "UCI HAR Dataset". The unzipping defaults to this folder name.

The folder should contain to subfolders, "train" and "test" as well as four text files: README.TXT, features_info.txt, features.txt and activity_labels.txt.

The content of the files are described in the Codebook.md in this repository.

In summary, the following files are used in the analysis:

**X_train.txt:** The activity measures that are captured by the smartphone

**subject_train.txt:** The list of individuals that correspond to the activity

**y_train.txt:*** The type of activity of the individual during the measurement

The same holds for the test set files: X_test.txt, subject_test.txt and y_train.txt

***nr. of observations**

test data:  2'947

train data: 7'352 

**features.txt:*** The list of activity measures i.e. the variable names

**activity_labels.txt:*** A list of possible types of activities 
## 
