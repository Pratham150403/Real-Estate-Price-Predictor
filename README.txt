			Real Estate Price Predictor
Obtained dataset of California Real-Estate prices from Kaggle. Cleaned the dataset.  Analysed the dataset to see the relationship between various housing parameters like total_bedrooms, total_rooms, population, median_income. Deduced a relation for parameter ocean_proximity to how rich the area is assigned an approximate numerical value to it. Analysed relationship between various housing parameters using graphs and removed the redundant variable.
Did feature extraction based on correlation obtained above. Shuffled the data randomly and split it  into train and test datasets.
Using sklearn library tried various ML models like Linear Regression,Decision Tree Classifier,K Neighbours Regressor,Random Forest Regressor and compared their results.
Obtained that Random Forest Regressor is best for this dataset and parameters used. 
