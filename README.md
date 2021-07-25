# Property project
## Summary of the project 
The property dataset is given with real estate information of the federal province of Buenos Aires, Argentina.
In the project, several machine learning models were developed in order to predict the price behavior of different types of properties. 


## Project 1
### Libraries using 
For this first project we will use the Numpy, Pandas, Matplotlib, Seaborn and Sklearn libraries, with the objective of developing several machine learning models and data visualization. 

### Exploratory data analysis 
At this point of the project we will seek to understand the dataset first. The form of the dataset, its columns and variables will be observed. We will analyze the missing values, the distribution of the variables, the relation and correlation between them. 

### Machine leaning models
In this section we took the federal capital as the best area for data analysis, and the property types house, PH and apartment as the most relevant.

Outliers and missing values were eliminated from the dataset, in search of a better model. 

At this point the Sklearn library was fundamental and several of its sublibraries were used, such as model_selection, linear_model, .tree, .neighbors, among others.

Subsequently, the dataframe was divided into 70% for training and 30% for testing. A linear regression model, a decision tree model and a nearest neighbor model were used to feed the dataframe. 

The data was analyzed with R2 and RMSE metrics, and a price prediction model was arrived at. 

## Project 2

### Objetive

The objective is to apply the built-in techniques (Data Transformation, Hyperparameter Optimization, Advanced Modeling, etc.) to generate a model that performs better than the model generated in the previous project.

## Transformation of data
In this notebook will be performed firstly the detection and elimination of outliers, encoding, imputation of missing values, data scaling and the generation of new predictor variables / dimensionality reduction (SVD/PCA).

Imputation will be performed through the analysis and modeling of 3 models, statistical, KNN and iterative, choosing the KNN model to perform the imputation. 

Outlier detection and elimination was performed using the IQR method on the three types of ownership with respect to price. Subsequently, the environments within each property type were analyzed and the same rule was applied. 

## Modeling

The modeling part was performed with more specialized algorithms than in the first installment, using Random Forest, BagggingRegressor, AdabootsRegressor and Stacking. Finally, RandomForest was chosen and tested in the two models, the current one and the one from the previous project, resulting in an improvement in the prediction of the price of real estate properties. 






