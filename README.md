# Google-Adsense-earning-prediction
Predicting Google adsense earning
I have my personal blog https://www.learnelectronicswithme.com/. Initially I posted posts related to electronics. But later when I started learning about data science, I starting posting related to data science, machine learning and deep learning.

From the adsense monthly report I collected datas and saved it in a excel file.
I did some exploratory data analysis. Since I entered manually the data was clean, no missing or null values. There was no much outliers. 

Then By univariate, bivariate and multivariate analysis I analyzed some patterns.
'Earnings($)', 'Page views', 'Page RPM($)', 'Impressions', 'Impression RPM($)', 'Active view Viewable(%)', 'Clicks'. These are the columns. Earning column is the dependent variable and 'Page views', 'Page RPM($)', 'Impressions', 'Impression RPM($)' are the independent variables. 

Then the model was evaluated. 
Mean Squared Error: 0.006142803569468601
R-squared: 0.8614605727486375
MSE of 0.006142803569468601 suggests that, on average, the squared difference between the predicted values and actual values is very low, indicating good predictive accuracy.

In a regression model. R-squared values range from 0 to 1, where 1 indicates that all of the variance in the target variable is explained by the model, and 0 indicates that the model doesn't explain any variance.

In this case, an R-squared value of 0.8614605727486375 means that approximately 86.15% of the variance in the target variable is explained by the model, which is generally considered a good fit for the data.

Then finally the earnings were predicted
