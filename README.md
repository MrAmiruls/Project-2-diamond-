# Project 4 - Diamond Price Prediction
This dataset contains the prices and other attributes of almost 54,000 diamonds
The whole of the dataset is in the shorturl.at/htwyY for your own work.
Diamond dataset was done by using Python Language on Spyder notebook.

## Data
There are 10 column including 7 of it is an input variables:
- Carat (Weight) : 0.2Kg - 5.01Kg
- Cut : Fair, Good, Very Good, Premium, Ideal
- Color : from J (Worst) to D (Best)
- Clarity : I1 (Worst), SI2, SI1, VS2, VS1, VVS2, VVS1, IF (Best)
- Depth length : 43% - 79%
- Table length : 43% - 95%
- Price (USD) : $326 - $18,823

Table is the width of the diamond table which is top or(flat surface) of the diamond.
Depth is the height of a diamond. It is measured from the culet(bottom) to the table(top) 
and divided by its average girdle diameter.

## Task
- Delete the unnecessary column in the table
- Split the data into features and label
- Encode the ordinal by categories for Cut, Color, and Clarity column
- Split the data into train-validation-test
- Perform feature scalling
- Using tensorflow keras to create Feedforward neural network
- Train and evaluate the model with validation data. Applying earlystopping and tensorboard for callback function
- Plot the data 

## Result
Loss, Mean Square Error and Mean Absolute Error
To see the difference between before arrange the categories by ascending order. 
### Before
![before](https://user-images.githubusercontent.com/85603599/164148746-8b4904ec-dd1d-47a9-9b87-0b98331dc2b8.jpg)
### After
![Screenshot 2022-04-20 095120](https://user-images.githubusercontent.com/85603599/164148853-c4edfcb2-6170-458a-8c51-6da0558a5d80.jpg)


## Graph
To see the difference between before arrange the categories by ascending order.
### before
![result](https://user-images.githubusercontent.com/85603599/164147271-49458ff4-de6c-460c-bdef-0e0a5529ebde.png)
### after
![results](https://user-images.githubusercontent.com/85603599/164147093-29448245-ee84-4496-897c-22dda4b799e7.png)


