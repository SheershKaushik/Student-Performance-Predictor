This project focuses on predicting students' math scores based on various demographic and educational factors using machine learning. The dataset is first explored and preprocessed to handle categorical variables like 
- gender
- race/ethnicity
- parental level of education
- lunch type
- test preparation course

Features are transformed using OneHotEncoder for categorical variables and StandardScaler for numeric variables. The dataset is then split into training and testing sets. Nine regression models— including 
1. Linear Regression 2. Lasso 3. Ridge 4. K-Neighbors Regressor 5. Decision Tree 6. Random Forest Regressor 7. XGBoost 8. CatBoost 9. AdaBoost are trained and evaluated using metrics such as Root Mean Squared Error (RMSE), Mean Absolute Error (MAE), and R-squared score.

Model performance on both training and test sets is compared and visualized using scatter plots and regression plots. The Linear Regression model achieved an accuracy score of approximately 83%, demonstrating its effectiveness in predicting math scores based on the provided features. 

This project showcases proficiency in data preprocessing, model training, evaluation, and visualization, making it suitable for inclusion in a technical portfolio highlighting skills in machine learning and data analysis.
