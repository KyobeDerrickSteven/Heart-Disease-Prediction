# Heart-Disease-Prediction

The dataset used was from Kaggle and can be found through this attached link.
https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction 


Bagging Classifier
Bagging also known as bootstrap aggregation refers to a technique of training models on different randomly selected subsets of the training data with replacement and generating various classifiers and reaching a final prediction through some sort of voting scheme in case of a classification task.
![image](https://github.com/KyobeDerrickSteven/Heart-Disease-Prediction/assets/118764834/4d8e574a-1d1c-4239-ab5b-9833ca9bca12)

Bagging involves selecting random subsets of data from the data pool with replacement. The unselected data points when training the model are added to the test set and are called Out-of-Bag samples.

Some of the advantages of bagging include.
- Reduced model variance due to more exposure of the random subsets of the dataset.
- Improved predicitive accuracy.
- Robustness as it enhances stability through reducing the impact of outliers and noise in the dataset by aggregation.
- Generates worse rate scenario results that are needed when diagnosing Heart Disease Patients.
  
The image below showcases the desired Machine learning model structure.

![image](https://github.com/KyobeDerrickSteven/Heart-Disease-Prediction/assets/118764834/7f228e8e-320b-4c9f-a308-1561c40fe53e)

Various Machine Learning Classifiers where used to form an ensemble and these included the following;
- Decision Tree Classifier
- Support Vector Classifier
- Random Forest Classifier
- XGBoost Classifier

The results indicated that the Bagging Ensemble model outperformed its counter parts that is the Unbagged/ Normal classfiers and Bagged single classifiers with an accuracy of 89%, F1-score of 90% and Specificity of 90%.

