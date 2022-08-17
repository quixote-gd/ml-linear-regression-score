### Summary 

Interested to explore basic machine learning.

Data mining approach to predict human wine taste preferences and to classify types of wine.

My purpose is to take another swipe at machine learning with various training models. Once again a large data set mix with red and white wine is considered.

This dataset is public available for research. The details are described in [Cortez et al., 2009]. 
Please include this citation if you plan to use this database:

P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis. 
Modeling wine preferences by data mining from physicochemical properties.
In Decision Support Systems, Elsevier, 47(4):547-553. ISSN: 0167-9236.

Available at: [@Elsevier] http://dx.doi.org/10.1016/j.dss.2009.05.016
              [Pre-press (pdf)] http://www3.dsi.uminho.pt/pcortez/winequality09.pdf
              [bib] http://www3.dsi.uminho.pt/pcortez/dss09.bib

### Questions

1. What will the wine quality be at the certification phase?
2. Predict (classification) what type of wine (white or red) based on chemical properties? 
3. Change the regression problem into classification by creating quality catergories. Ex: 1-3, 4-7, 8-10 for low, medium, and high quality.

### Features
fixed acidity, volatile acidity, citric acid, residual sugar, chloride, free sulfur dioxide, total sulfur dioxide, density, pH, sulphates, alcohol, quality

### Model Choice

For Question 1: Trained the data on Linear Regression, Decision Tree Regression, and Random Forest Regressor model. I decided to use Random Forest Regressor because the other models underfitted and overfitted the data.

For Question 2: Change the regression problem into classification by creating quality catergories. Ex: 1-3, 4-7, 8-10 for low, medium, and high quality.

### The Process
1. Gain some insights and some visualizations.
2. Create test and train sets.
3. Prep data for ml.
4. Run ml model


