# Credit-Risk-Clustering
Credit default classification using logistic regression and KNN on UCI’s Taiwan dataset. Includes engineered features, cross-validation, and ROC/AUC visualizations

This project uses the Taiwan Credit Default dataset from the UCI Machine Learning Repository to build and evaluate models that classify whether a credit card client will default in the following month.

Two supervised learning models were implemented — Logistic Regression and K-Nearest Neighbors — using both raw and engineered features. The models were evaluated with 5-fold cross-validation, achieving an average classification accuracy of ~80%.

Custom behavioral risk features such as weighted_pay_delay, avg_balance, and total_payments were engineered to improve model interpretability and reduce dimensionality.

Model performance was assessed using accuracy, ROC-AUC, RMSE, and confusion matrices. Visualization of ROC curves was performed with matplotlib and seaborn to highlight trade-offs between classification thresholds.

Libraries used: pandas, scikit-learn, statsmodels, numpy, seaborn, matplotlib.

