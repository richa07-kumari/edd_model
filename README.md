This use case is basically predicting the estimated delivery date of the orders placed within United States based on various parameter like location, dimension, holday constrains, etc. I have divided trhe complete use case in 6 phase: Starting from synthetic data generation, data cleaning, feature engineering, defining models, evaluating them and then final deployement.
The stages in brief are as:
1. Synthetic data generating- Creating a 6-month synthetic dataset storing order details and then adding intentional noise to make a replica of real-world data.
2. Data Cleaning and EDA- Cleaning data and then plotting the time taken distribution based on the past data available, first graph shows a broader view and second graph shows how much time taken in average at  ecah stage of order processing.
3. Feature Engineering- Transforming dimension into company standard volumetric weight and also defining the peak days in general.
4. Creating model- Spilted dataset into train test and trained four models over the training dataset.
5. Evaluating for best model- Calculated Huber loss for each and then see the pairwise comparison of performance productivity between each of the models
6. Deployement- Takes the best fit model from previous phase and use it in our final function. Now user defines the product and location for getting the delivery date predicted.

