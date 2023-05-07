# HeartAttackPrediction

This project uses the https://www.kaggle.com/datasets/rashikrahmanpritom/heart-attack-analysis-prediction-dataset dataset for heart attack analysis and prediction and a combination of machine learning models to find what feautures are most important in prediction, and how accurately feauture heart attacks can be predicted. 
a randomized training and testing split was done through randomly generated indices and saved. This particular set was then used in both the neural network and a single logistic regression model to compare the effectiveness of the two model types.
ensemble methods with logistic regression models were alse used by creating 40 different log reg models based on 40 different randomized training and testing splits. the values for the weights were then examined and averaged to determine which feautures had the strongest correlations.
