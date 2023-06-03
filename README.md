****# Air-quality-index-AQI-****

The air quality index (AQI) is used for the effective assessment of air quality. This process transforms the data of various pollutants into a single number or value. AQI is categorized into the following six different categories: good, satisfactory, moderately polluted, poor, very poor, and severe. The AQ sub-index was developed for tracking eight pollutants (PM 2.5, PM 10, SO2, NO2, CO, NH3, O3, and Pb).

****Business Objective:****

To analyse the air pollution in various stations by using the Air Quality Index. AQI is used by government agencies to communicate the pollution of air in different stations.

****Approach:****:


• Data cleaning, treating missing values, removing redundant columns, outlier treatment, and making data more 
readable was done initially
About me
Skills
 Projects
• EDA was performed to create inferences
• VIF method was used to treat the multicollinearity
• Feature importance was calculated and significant features were taken for the further process
• Linear Regression, Decision Tree Regressor and Random Forest Tree Regressor are some regression models used to 
predict the AQI of different states
• Random Forest was the best model with a good RMSE value.

****CONCLUSION:**** 

From the above models we created, we found XGB and LGBM are reliable and consistent. So, we can use these models on a new set of data and be used for real time prediction. Now the question is which model should be used among these two.The XGB Regressor is more reliable than the LGBM Regressor because the RMSE score of test data is significantly less.In future a dataset can be collected and this model can be used to predict the AQI_score.
