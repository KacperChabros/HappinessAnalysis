# Happiness Analysis based on Economic and Social Factors
I've created this project with [faboulousfoxx](https://github.com/fabulousfoxx) as a part of our Data Exploration course. The first aim of the project was to perform exploratory analysis of the selected dataset and state a hypothesis about the data. The second goal was to create a regression model explaining the trend in the dataset in order to confirm or refute a hypothesis.  

## Research Methodology
Given dataset consists of 10 features aiming to describe output, continuous feature - `Life Ladder`. Firstly, we performed exploratory analysis of the dataset. We analysed and imputed missing data using approximation. Then we analysed the distributions of each feature, removed the outliers using IQR method with empirically selected multipliers for each feature and repeated the analysis. After grouping the data based on continents we formed the following hypothesis:  
`different factors influence the level of perceived life satisfaction depending on the region of the world`.  
Then we created models using multiple regression, regularization and ensemble learning methods and tested their performance and importances of the features. We also engineered a few new features based on the ones already existing in the dataset. Those experiments were repeated on the full dataset as well as on each subset containing data from a single continent.  
We then analysed the outcome and summarised the findings in the last section of the notebook.

## Methods Used
* Multiple Regression
* L2 and L1 Regularization Methods
* Feature Selection Methods:
    * Exhaustive Search
    * Forward Stepwise
    * L1 regularization to exclude some features
* Ensemble Learning:
    * Random Forest Regressor
    * XGBoost Regressor
* Feature Engineering

## Technologies
* Python and its libraries
    * Pandas
    * Numpy
    * Matplotlib
    * Seaborn
    * Plotly
    * Sklearn
    * XGBoost

## Setup and usage
The notebook is rendered, one can simply browse it on GitHub or download it and browse locally. To re-run it, one should install all the necessary libraries and simply run the cells.

## Credits
* I created this project with:
    * [faboulousfoxx](https://github.com/fabulousfoxx)