# Practice-Market-Mix-Modelling
This repository is the showcase of Marketing Mix Modeling ideas, skills for regression modelling along with that, exploratory data analysis using pandas, matplotlib and seaborn etc. For regression, as of now only OLS is being implemented. The work for this repository is still in progress.
The dataset contains TV, Radio, Newspaper as Predictor Variables(Independent features) and Sales as Target Variable(Dependent feature).
Along with that there is an index column. We have created a date column instead of keeping that Index column and the dataset has become a weekly dataset.
The dataset is basically an advertising related dataset which has ATL (Above the Line) features which targets mass audiences.
A couple of regression models have been built here to check which model can explain the most variablity of the dataset, in other words the model having high Adjusted R-Square value and having all the statistical significant variables.
After creating the base models, I have introduced lagged features also for experimental purpose to check if any of those features can also be kept as significant for contributing towards Sales or ROI.
