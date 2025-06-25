# Financial-Analysis-model
Assessing the creditworthiness of individuals is crucial for both loan approval and risk management. The credit score of a person is a significant metric used by financial institutions to determine the likelihood that an individual will repay their loans or credit balances. Accurate classifications of credit scores can be counted as an aid towards financial companies like PaisaBazaar, enhancing their credit assessment processes, reducing the risk of loan defaults, and offering financial advice to their customers. This project focuses on creating a machine-learning-based regression model that predicts the credit scores of individuals on the basis of various features, credit card usage, and payment behaviour.
This project focuses on creating a machine-learning-based regression model that predicts the credit scores of individuals on the basis of various features, credit card usage, and payment behaviour.
Objective
The goal of this project is to build a model that analyse and classify credit scores based on customer data. Hence, improve decision making processes and contribute to better financial product recommendations.

Data Preprocessing and feature engineering

The project begins with uploading and loading the customer dataset using files.upload() in Google Colab. The data is initially inspected (checking for nulls or missing values), encoding the 'Loan_Type' for modeling atlast, feature scaling.
Further, this enhance the dataset's predictive capability by providing more relevant structured information.

Modeling and Evaluation

Train, test, split is the main method used for the modelling. Further, evaluation techniques such as mean squared error and root mean squared error has been used. Input= model = LinearRegression() model.fit(X_train, y_train) y_pred = model.predict(X_test) rmse = np.sqrt(mean_squared_error(y_test, y_pred)) print(f'Root Mean Squared Error: {rmse:.2f}') Output= Root Mean Squared Error: 2.15

Conclusion

This project successfully demonstrates how machine learning can be applied to predict credit scores using customer data. By cleaning and transforming raw data, engineering relevant features, and using robust regression models with proper tuning, it is possible to gain valuable insights into a person's credit score to determine the probability of an individual to pay their loans or credit balances. This type of predictive model can give accurate classifications of credit scores, enhancing the credit assessment process, reducing the risk of loan defaults, and offering financial advice to the customers.
