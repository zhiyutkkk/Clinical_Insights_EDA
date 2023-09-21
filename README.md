# Clinical_Insights_EDA

The registry dataset has many missing values and outliers. I found a linear pattern between the missing values and utilized linear regression to fill in the missing values instead of simply using median values. I then used the simple random oversampling method to create a more balanced dataset. Finally, I conducted the Kruskal-Wallis test and Dunn's test on three different datasets with and without oversampling to determine that a patient's pulmonary embolism location is having a statistically significant impact on procedure time, fluoroscopy time, and catheter time. 
