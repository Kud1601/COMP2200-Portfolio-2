In Portfolio Two, we're revisiting the same dataset from Portfolio One, 
but this time, it's the cleaned version without any null or missing values. 
The analysis becomes more intricate compared to Portfolio One.

We start by importing essential packages such as Seaborn, Pandas, Matplotlib, etc.,
and then re-reading the data file to perform correlation analysis. 
Correlation helps determine the dependent value based on the value of 
an independent variable. Additionally, we aim to make predictions on the dataset 
by training classification models.

For correlation analysis, it's crucial to select only the most necessary features.
Categorical columns are converted to numerical values using encoder.fit to enable
linear regression analysis.

The subsequent part of the portfolio focuses on splitting and training the model 
to make predictions for the future. The dataset is split into two ways:
90% and 10% for training and testing purposes. We then analyze the shape of the 
model in both cases.

Next, we identify the most and least correlated features. 
For instance, the most correlated features are gender and helpfulness, 
while the least correlated are review and gender. Based on these features, 
we create models according to the specifications outlined in the portfolio:

- Model A: Training with 10% most correlated features
- Model B: Training with 10% least correlated features
- Model C: Training with 90% most correlated features
- Model D: Training with 90% least correlated features

After creating the models, they need to be evaluated to choose the best fit.
However, there are errors in the code that prevent this evaluation. Ideally,
this evaluation should be done by calculating the Mean Squared Error (MSE)
and Root Mean Squared Error (RMSE) of each model.

The last part of this portfolio focuses on data ethics and how to mindfully
analyze any dataset. Potential errors are discussed, and their effects on
the dataset results are highlighted. This serves as a reminder of the importance
of ethical considerations and thorough analysis in any data-related endeavor.
