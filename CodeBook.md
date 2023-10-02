# About the source data
The source data are from the Human Activity Recognition Using Smartphones Data Set.
A full description is available at the site where the data was obtained:[here](http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones)
And the Data set for this project is obtained [here](https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip)

# About R script
## Step 1: Data Preparation and Merging
*1.1* Reading Files

* Read training dataset.

* Read testing dataset.

* Read the feature vector.

* Read activity labels.


*1.2* Assigning Variable Names

Assign appropriate variable names.


*1.3* Merging Data

* Combine all the data into one unified dataset.

## Step 2: Extracting Relevant Measurements
* Extract only the measurements related to mean and standard deviation for each measurement.


## Step 3: Activity Labeling
* Label the activities in the dataset with descriptive activity names.

## Step 4: Variable Naming
* Label the dataset with descriptive variable names for clarity.

## Step 5: Creating a Tidy Dataset
**5.1**: Generating Tidy Data
Create a second, independent tidy dataset.

**5.2**: Exporting Tidy Data

Save the second tidy dataset as a text file.
Note: This script assumes that all the required data is available in the same folder, without compression, and with original names intact.  

## Variables
**x_train**, **y_train**, **x_test**, **y_test**, **subject_train**, and **subject_test** contain data from downloaded files.

**x_data**, **y_data**, and **subject_data** merge the datasets for further analysis.

features holds the correct names for the **x_data** dataset, which are applied to the column names.
