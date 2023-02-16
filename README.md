# TokyoRealEstatePricePrediction

This project creates a Real Estate Prices Prediction model for tokyo.

1.Dataset for this project can be accessed via below URL:-

https://www.kaggle.com/datasets/nishiodens/japan-real-estate-transaction-prices

※Note:The above url contains Real estate prices dataset for japan.But this project 
deals with just tokyo area.So download only the real estate prices dataset for tokyo 
prefecture.

2.After downloading the dataset , use 'Cleaning Data.ipynb' to clean the input dataset 
containing real state prices data for tokyo.After execution of this notebook, 
'save_cleaned.csv' file is generated.

3.Next execute 'Real estate prices prediction.ipynb' which will generate the pickle model 
for prediction of real estate prices in tokyo.

※Note:4 algorithms (Random Forests, SVR,K Nearest Neighbors and DecisionTrees)are compared 
for prediction.Best results are achieved with Random Forests resulting in 18.8% mean absolute
precentage error.
