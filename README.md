# Credit-Card-Fraud
Prediction of Fraud Credit Card Transactions.
This project focuses on detecting fraudulent credit card transactions using a Random Forest Classifier with a highly imbalanced dataset of 284,807 transactions. To address the imbalance, Random Undersampling was applied, achieving a balanced representation of classes. The model, trained on the resampled data, achieved an accuracy of 91.41%. Further improvement was achieved through Hyperparameter Tuning using RandomizedSearchCV, optimizing parameters such as the number of estimators and maximum depth.

The project leverages libraries like Pandas and NumPy for data handling, Matplotlib for visualization, Scikit-learn for model building and evaluation, and Imbalanced-learn for resampling. This work highlights the importance of balancing data and tuning models to enhance performance in fraud detection systems.
