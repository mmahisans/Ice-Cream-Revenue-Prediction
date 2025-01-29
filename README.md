# Ice-Cream-Revenue-Prediction
Predicting Ice Cream Revenue using Quadratic regression and Linear interpolation

Dataset Used: https://www.kaggle.com/datasets/sakshisatre/ice-cream-sales-dataset

## Method
1. Load the CSV file into Google Colab
2. Import pandas, skelearn, and matplotlib libraries
3. Input the data pd.read and determine the x and y variable
   
### Linear Interpolation
1. Split the data to 8:2
2. Sort the training set
3. Define the predict function for linear interpolation
4. Calculate the errors for the testing set using MAE, MSE, and RMSE
5. Create the data viz
6. Create the prediction function for predicting y with new x and input the desired x

### Quadratic Regression
1. Split the data to 8:2
2. Define the quadratic function
3. Fit the function to the data using params
4. Predict the testing set
5. Calculate the errors for the testing set using MAE, MSE, and RMSE
6. Create the data viz
7. Create the prediction function for predicting y with new x and input the desired x
