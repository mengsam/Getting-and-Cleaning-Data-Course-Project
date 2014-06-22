Description of the run_analytics.R process

1. Assign definitions
2. Loads library "plyr"
3. Downloads required data from "http://archive.ics.uci.edu/ml/machine-learning-databases/00240/UCI%20HAR%20Dataset.zip"
4. Creates results folder
5. Loads feature data set features.txt used for columns
6. Loads and appends train dataset using X_train.txt, y_train.txt, subject_train.txt:
Subject_train contains the ids
Y_train contains the activity labels
X_train contains the data using the feature data set as columns
7. Loads and appends test dataset using X_test.txt, y_test.txt, subject_test.txt:
subject_test contains the ids
y_test contains the activity labels
X_test contains the data using the feature data set as columns
8. Appends train and test data
9. Rearrange the data using id
10. Saves data to datasetQ1.csv
11. Extracts the mean,std into datasetQ1
12. Saves revised data to datasetQ2.csv
13. Loading activity labels activity_labels.txt
14. Changes the data activity row to use the activity labels
15. Calculates mean on activity for each id
16. Appends _mean to all data columns
17. Saves the tidy dataset to datasetQ5.csv
