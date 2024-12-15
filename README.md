This project addresses predicting customer interest in credit card offers using machine learning, with Random Forest emerging as the best-performing model, 
achieving a precision score of 0.85. Five models were tested, including Random Forest, SVM, Logistic Regression, XGBoost, and KNN, with Random Forest consistently outperforming others across varying dataset sizes.
Feature importance analysis identified Credit Product, Vintage, and Age as the most critical predictors. 
To improve the model, techniques like weight reassigning for better recall, feature engineering (PCA), model stacking, and leveraging stronger GPUs for larger datasets are proposed.

Required library version:

python=3.12.5
matplotlib=3.9.2
plotly=5.23.0
pandas=2.2.2
scikit-learn=1.5.1
numpy=1.26.4
py-xgboost=2.1.1
shap=0.45.1
jupyter
