# Wine-Quality-Prediction-Using-Machine-Leaarning
## About the dataset
The two datasets are related to red and white variants of the Portuguese "Vinho Verde" wine. Due to privacy and logistic issues, only physicochemical (inputs) and sensory (the output) variables are available (e.g. there is no data about grape types, wine brand, wine selling price, etc.).
These datasets can be viewed as classification or regression tasks. The classes are ordered and not balanced (e.g. there are many more normal wines than excellent or poor ones). Outlier detection algorithms could be used to detect the few excellent or poor wines. Also, we are not sure if all input variables are relevant. So it could be interesting to test feature selection methods.

## About the model
This project was carried out to build a machine learning model for predicting the good from the bad wine. I did some exploratory data analysis and then proceeded to balance the dataset. I built three different models amd chose the best model with a high accuracy. 
This analysis was carried out with python. Some of the packages I used include Scikit-learn, Pandas, Matplotlib, Seaborn etc. 

## Data Gathering
This dataset is available on UCI machine learning repository, https://archive.ics.uci.edu/ml/datasets/wine+quality.
Citation: P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis. Modeling wine preferences by data mining from physicochemical properties. In Decision Support Systems, Elsevier, 47(4):547-553, 2009.
Relevant publication
P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis. Modeling wine preferences by data mining from physicochemical properties. In Decision Support Systems, Elsevier, 47(4):547-553, 2009.

## Attribute Information:
Input variables (based on physicochemical tests):
1. fixed acidity
2. volatile acidity
3. citric acid
4. residual sugar
5. chlorides
6. free sulfur dioxide
7. total sulfur dioxide
8. density
9. pH
10. sulphates
11. alcohol
12. quality

