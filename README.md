# Practical-ML
Module 8 Week 4 Assignment


## Background

Using devices such as Jawbone Up, Nike FuelBand, and Fitbit it is now possible to collect a large amount of data about personal activity relatively inexpensively. These type of devices are part of the quantified self movement – a group of enthusiasts who take measurements about themselves regularly to improve their health, to find patterns in their behavior, or because they are tech geeks. One thing that people regularly do is quantify how much of a particular activity they do, but they rarely quantify how well they do it. In this project, your goal will be to use data from accelerometers on the belt, forearm, arm, and dumbell of 6 participants. They were asked to perform barbell lifts correctly and incorrectly in 5 different ways. More information is available from the website here: http://web.archive.org/web/20161224072740/http:/groupware.les.inf.puc-rio.br/har (see the section on the Weight Lifting Exercise Dataset).

## Analysis Done

Data
The training data for this project are available here:
https://d396qusza40orc.cloudfront.net/predmachlearn/pml-training.csv
The test data are available here:
https://d396qusza40orc.cloudfront.net/predmachlearn/pml-testing.csv

The above linked data was used for the analysis, cleaned the data, processed it, trained a tree as well as random forest model with the help of cross-validation and
finally tested on the test data to predict the 'classe' variable.

## Some more insights

From the confusion matrices we got, the Random Forest algorithm performes better than decision trees. The accuracy for the Random Forest model was 0.99 (95% CI: (0.993, 0.997)) compared to 0.47 (99% CI: (0.45, 0.49)) for Decision Tree model.
The expected out-of-sample error is estimated at 0.005. The expected out-of-sample error is calculated as 1 - accuracy for predictions made against the cross-validation set. Our Test data set comprises 20 cases. With an accuracy above 99% on our cross-validation data, we can expect that very few, or none, of the test samples will be missclassified.
