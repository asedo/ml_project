# ml_project
Coursera Machine Learning Project

This is the README for the Coursera Machine Learning Project


The goal of this project is to look at a training data set that came from accelerometers on the belt, forearm, and dumbell of 6 participants which were asked to perform the exersizes correctly and incorrectly in 5 different ways. Using this data, we are to build a model and decide if the test set of 20 activities are doing the excersize corrrectly, or incorrectly. 
In general we will follow the following process. 
1. load the data into a data frame
2. Check for data problems such as: irrelevant columns, missing values, out of range, etc.
3. Prepare the data for processing
4. Split or partition the data into training and testing data frames
5. Make sure classe a factor variable. 
6. Create a data model from the training data using the train function
7. Use predict function to run the testing data through the model created by training data.
8. use the confusionmatrix to compare accuracy of model
9. predict the values from the 20 example observations and get the results
##About the Data set...

The training data used for this project are available here:
  
  https://d396qusza40orc.cloudfront.net/predmachlearn/pml-training.csv

The test data are available here:
  
  https://d396qusza40orc.cloudfront.net/predmachlearn/pml-testing.csv
Note: this pml-testing data contains 20 cases which we will use to predict if person is doing the exercise correctly.

The description for this project comes from this source: http://groupware.les.inf.puc-rio.br/har
Let's set up the environment.




