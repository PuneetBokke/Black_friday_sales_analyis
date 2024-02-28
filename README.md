# Black_friday_sales_analyis

I have  completed a data analysis project with a dataset comprising 537,577 rows and 12 columns. The dataset includes information on user transactions with the following features:

User_ID: Unique identifier for users (5891 users in total).
Product_ID: Unique identifier for products (3623 products in total).
Gender: Indicates the gender of the person making the transaction.
Age: Indicates the age group of the person making the transaction.
Occupation: Numerically labeled occupation of the user (0 to 20).
City_Category: User's living city category, categorized into 'A', 'B', and 'C'.
Stay_In_Current_City_Years: Indicates how long the user has lived in the current city.
Marital_Status: 0 if the user is not married, 1 otherwise.
Product_Category_1 to _3: Categories of the product, labeled with numbers.
Purchase: Purchase amount.
I utilized the XGBoost algorithm for regression and achieved an Mean Squared Error (MSE) of 8,338,027.56 and an R-squared score of 0.668. These metrics indicate that the model performed reasonably well in predicting purchase amounts, with the MSE representing the average squared difference between predicted and actual values, and the R-squared score indicating the proportion of variance in the dependent variable captured by the model.

This project aimed to analyze user transactions, providing valuable insights into the factors influencing purchase amounts. The XGBoost model, with its high R-squared score, demonstrates its effectiveness in capturing patterns within the dataset. Future work may involve further feature engineering, model tuning, and exploration of additional algorithms for enhanced performance.
