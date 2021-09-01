# TEA SALES REGRESSION 🍵

### 1. Problem Definition
To analyse the temporal nature of tea prices in the training dataset and forecast the weekly average tea price for the 29 weeks mentioned in the test set.

### 2. Dataset
Data is taken from [MachineHack Competition](https://machinehack.com/hackathons/teastory_weekend_hackathon_edition_2_the_last_hacker_standing/overview)

Train.csv — 544 rows x 15 columns (includes ‘Average’ as a target variable)

Test.csv — 29 rows x 15 columns

### 3. Evaluation
The submission will be evaluated using the RMSE metric. One can use One can use ‘np. sqrt (Mean Squared Error)’ to calculate the same.

### 4. Modeling
After cleaning and imputing all the missing values in the dataset. I tried various Regression models, but two models performs well,  
- **GradientBootingRegressor** with **RMSE of 2.66**
- **CatBoostRegressor** with **RMSE of 3.34**.
