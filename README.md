# Stock-Price-Prediction-Using-Regression

### Dataset: S&P 500

The combined dataset of 500 companies was used to visualize and predict the stock prices.

#### Preprocessing

Some preprocessing was done to get extra informative columns like WeekDay, WeekDay Number, etc.

The missing values were replaced by the mean of previous and next days values. Then using spearman coefficient, strength between different columns were taken out. This gave that OPEN and HIGH prices are closely related and CLOSE and LOW prices are closely related. Then different regression techniques were applied to predict OPENING and CLOSING Prices of the Stocks.

### The least mean absolute error (among all) obtained was 0.0034761.

### NOTE: Extraxt the rar file to get the dataset of S&P 500.
