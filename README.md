# Electric-Vehicle-Project

# REPORT
Introduction

The ML model objective is to predict the likelihood of the price a vehicle be brought or sold?(Expected Price ($1k)) given a set of indicators with columns name 'Make', 'Model','Base MSRP','Electric Vehicle Type','Electric Range','Clean Alternative Fuel Vehicle (CAFV) Eligibility'.

The dataset ("Electric_cars_dataset.csv") has a size of 5.9mb, with 18 columns and 43199 rows entries.

Methodology

There were 1455 missing values, and there was presence of outliers in 'Expected Price ( 1𝑘)′,𝑖𝑡𝑤𝑎𝑠𝑑𝑒𝑎𝑙𝑡𝑤𝑖𝑡ℎ𝑢𝑠𝑖𝑛𝑔𝑖𝑛𝑡𝑒𝑟𝑞𝑢𝑎𝑛𝑡𝑖𝑙𝑒𝑟𝑎𝑛𝑔𝑒.𝐿𝑎𝑏𝑒𝑙𝑒𝑛𝑐𝑜𝑑𝑒𝑟𝑤𝑎𝑠𝑢𝑠𝑒𝑑𝑡𝑜𝑑𝑒𝑎𝑙𝑤𝑖𝑡ℎ𝑡ℎ𝑒𝑐𝑎𝑡𝑒𝑔𝑜𝑟𝑖𝑐𝑎𝑙𝑣𝑎𝑟𝑖𝑎𝑏𝑙𝑒𝑠𝑋𝑎𝑛𝑑𝑌𝑤𝑎𝑠𝑒𝑠𝑡𝑎𝑏𝑙𝑖𝑠ℎ𝑒𝑑,𝑡ℎ𝑒𝑑𝑒𝑝𝑒𝑛𝑑𝑒𝑛𝑡𝑣𝑎𝑟𝑖𝑎𝑏𝑙𝑒𝑖𝑠′𝐸𝑥𝑝𝑒𝑐𝑡𝑒𝑑𝑃𝑟𝑖𝑐𝑒( 1k)' the test size was set as 20%(0.2) and the train would be 80%. Support Vector Machine (SVM) was the model used. mean absolute error, mean squared error, rsquared score were used as the performance metrics. Results The result on the test set are as follows: Mean Absolute Error (MAE): 5.14 Mean Squared Error (MSE): 90.68 R-squared (R²): 0.82

Discussion The results of the SVM regression model show promising performance in predicting the expected price of electric vehicles. The model achieved a mean absolute error (MAE) of $5.14,a mean squared error (MSE) of 90.68, and an R-squared (R²) score of 0.82.

The low MAE indicates that, on average, the model's predictions are within 5.14 of the true expected price. The MSE of $90.68 suggests the model is making relatively small errors on average, without being overly sensitive to outliers or large errors. The R-squared score of 0.82 implies the model is able to explain 82% of the variance in the expected price of electric vehicles. This is a strong result, indicating the input features (make, model, MSRP, electric vehicle type, electric range, and CAFV eligibility) are highly predictive of the target variable.

These performance metrics suggest the SVM regression model is well-suited for this task and could be a useful tool for stakeholders in the electric vehicle market. The model appears to be capturing the key relationships between the input features and the expected price, allowing for reasonably accurate predictions.

