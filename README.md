# Heart-Disease-Prediction-using-DNN

This Self-project titled "Heart Disease Prediction" project aims to provide a method for heart disease prediction. The model predicts if the patients have a heart disease or not. The dataset (available in repository) contains more than 10 features. After data visualisation, I end up with 8 features those are important for prediction. I have utilized both Federated Learning (FL) and traditional Centralized Learning, attaining around 83.9\% accuracy for centralized learning and 80\% for FL.

Although centralized learning provides slightly higher accuracy, it is at the cost of potential privacy leakage & security compromise. But, FL addresses these significant issues with only slightly lesser accuracy. Subsequently, I developed an API using FastAPI for deployment in the cloud. For this task, I employed a three-layered Deep Neural Network (DNN). 

# Model Architecture
![MA](https://github.com/RishabNeo/Heart-Disease-Prediction-using-DNN/blob/main/Images/Model%20Architecture.png)

# Model accuracy vs number of epochs
![plot](https://github.com/RishabNeo/Heart-Disease-Prediction-using-DNN/blob/main/Images/plot%20(HD).png)
