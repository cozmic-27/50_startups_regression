# 50_startups_regression

Multiple Linear Regression is employed to determine the profit of 50 startups based on factors that include R&D spending, administration costs, marketing, and state of operation.

The dataset is imported and ‘profit’ is separated as our Y value to predict. 

The variable ‘state’ is categorical so we must encode it to fit our dataset. OneHotEncoder is used to assign each of the three states binary values for simplicity. It is also used to eliminate any false presumptions about the ‘order’ of California, Florida, and New York.

The data set is split into training and test sets in order to train our model on a sample and show the accuracy of it on unseen data.

## Predicting the Test Results

The score computes what is known as the ‘R2 value.’ The number 0.9501.. indicates that our model can account for ~95% of the variance in the response variable. 

The coefficients measure to what degree our response variable is adjusted for every unit of change in a predictor variable (all other predictors held constant). In other words, if we take ‘Administration’ for example and increase spending in this column by a given percent (or units) how much will our profit increase or decrease?

The intercept is used to measure a baseline value for our profit. Or rather, with all of our predictors held at their mean values what would our starting profit be?

Finally, the test scores and predicted scores are concatenated into an array to show the model's accuracy.

 A function is written for the user to input values and the model will predict the profit.


## Installation 

Install Anaconda Python 3.6 version
https://conda.io/docs/user-guide/install/index.html

Install Python 3.6
https://www.python.org/downloads/release/python-360/

Install Jupyter Notebook
https://jupyter.org/install

## Credits

“50- Startups” Dataset taken from Udemy Course: "Machine Learning A-Z: AI, Python and R + ChatGPT Bonus [2023].” 

