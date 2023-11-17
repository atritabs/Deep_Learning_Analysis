# Alphabet Soup Charity Optimization Notes

## Overview of the Steps Used


### Data Processing Optimization


1) Decided to keep the 'Names' column in order to improve further analysis on the data.
2) Analyzed the number of values that were associated with each 'Name Counts'.
3) Created a custom cutoff for the names, which is at least repeated 10 times or more.
4) Create a modified Dataframe to help capture better results and variability in the overall data that is to be used.
5) Created a separate row, where the unique repeated name values were less than '10', and they were grouped as a separtate variable where
   the values were less than 10.
6) Modified the number of 'input' features that are to be implemented, using the scaled data set
    a) Analyzed the 'hidden layer' values, and split the nodes to account for the change as '14' & '7' respectively.
7) Trained the model using X_train_scaled information ; and assigned a validation split of 0.15 and epochs = 50


### Compiling, Training, and Evaluating the Model

1) Utilized the activation functions of "relu" and "sigmoid"
2) Choose the hidden layers to split as 14 & 7 to create uniue values
3) Able to achieve the target performance of 78%

### Summary

The data model in inself was optimized was appropirately categorizing the names column, and adding more relevance to the data set. Also, 
optimizing the data to group values that were insignificant helped to create a better X_train_scaled data set, which in turn helped to create more meaningful insights from the overall data.