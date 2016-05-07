# Practical-Machine-Learning
##Please Note:to view the html file online, please go to [link](http://yanyu6.github.io/Practical-Machine-Learning).
##Prediction Assignment Writeup 
###Background

Using devices such as Jawbone Up, Nike FuelBand, and Fitbit it is now possible to collect a large amount of data about personal activity relatively inexpensively. These type of devices are part of the quantified self movement – a group of enthusiasts who take measurements about themselves regularly to improve their health, to find patterns in their behavior, or because they are tech geeks. One thing that people regularly do is quantify how much of a particular activity they do, but they rarely quantify how well they do it. In this project, our goal will be to use data from accelerometers on the belt, forearm, arm, and dumbell of 6 participants. They were asked to perform barbell lifts correctly and incorrectly in 5 different ways. More information is available from the website here: http://groupware.les.inf.puc-rio.br/har (see the section on the Weight Lifting Exercise Dataset).

###Data

The training data for this project are available here:

https://d396qusza40orc.cloudfront.net/predmachlearn/pml-training.csv

The test data are available here:

https://d396qusza40orc.cloudfront.net/predmachlearn/pml-testing.csv

###Summary
The goal of this project is to predict the manner in which people did the exercise. Our outcome is the "classe" variable in the training set. In this report, after we load the data sets, we first do data cleaning, cross validtaion, and preprocessing. Then we build a tree model, a boosting with tree model, and a random forest model. Among those three models, the random forest model has the highest overall accuracy(0.9922). Thus, we choose the random forest model as our final model and use it to predict 20 different test cases.
