# Deep Learning Homework: Charity Funding Predictor

### Overview

The non-profit foundation Alphabet Soup wants to create an algorithm to predict whether or not applicants for funding will be successful. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, you have received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years.


### Results

  * Data Preprocessing
    * The target variable is the IS_SUCCESSFUL column.
    * The feature variables would be all the columns except the target variable IS_SUCCESSFUL column. 
    * What the variables are neither targets nor features are the EIN and NAME columns which were dropped.
  * Compiling, Training, and Evaluating the Model
    * The neural network model has 3 hidden layers. My first layer had 100 neurons, the second has 50 and the third has 10 neurons there is also an output layer. The first, second and third hidden layers have the "sigmoid" activation function and the activation function for the output layer is "sigmoid.
    * The model was not able to reach 75% accuracy 73% is the accuracy of the model.
    * Multiple attemps to increase the model was made, includeing using different activation functions for the hidden layers, adding more neurons to a hidden layer and adding and reducing the number of epochs to the training regimen

### Summary

The model was only able to reach an accuracy of 73% while stay within the assigned requirements falling short of the 75% target. Although the requirements ask for the removal of the NAME column if it is included in the dataset an accuracy of 79% is reached.

