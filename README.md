# Credit-Card-Fraud
Prediction of Fraud Credit Card Transactions.
This project focuses on detecting fraudulent credit card transactions using a Random Forest Classifier on a highly imbalanced dataset of 284,807 transactions. To address the imbalance, Random Undersampling was applied, achieving a balanced dataset. The default model achieved an accuracy of 93.40% on resampled data and 97.050% on the original imbalanced dataset. After Hyperparameter Tuning with RandomizedSearchCV, the tuned model achieved 93.91% accuracy on resampled data and 96.99% on the original dataset, reducing false negatives and improving sensitivity to fraudulent transactions.

Focusing on F1-score during tuning ensured better handling of the minority class, balancing precision and recall. Adjustments to key hyperparameters like min_samples_split and min_samples_leaf improved detection of rare fraud patterns. This project highlights the importance of resampling techniques, hyperparameter tuning, and class-specific metrics in building effective fraud detection systems. Libraries like Pandas, NumPy, Scikit-learn, and Imbalanced-learn were critical to this success.
