INTRODUCTION :-
In this project, the objective is to compare the performance of different machine learning
models for predicting house prices. The California Housing dataset was used, which
contains various features such as median income, house age, number of rooms,
population, and geographical location. The goal is to evaluate multiple regression
models and identify the best-performing model.
METHODOLOGY :-
1.Dataset :-
The California Housing dataset was loaded using scikit-learn. The dataset
contains numerical features related to housing characteristics and the target
variable is house price.
2.Data Preprocessing :-
The dataset was converted into a pandas DataFrame. The features were
separated into independent variables (X) and the target variable (Y). The data
was split into training and testing sets using an 80-20 split.
3.Models Used :-
The following machine learning models were implemented:
● Linear Regression
● Ridge Regression
● Decision Tree Regression
4. Evaluation Metrics :-
The models were evaluated using Root Mean Squared Error (RMSE) and R²
Score to measure prediction accuracy and model performance.
RESULTS :-
The performance of the models was compared using RMSE and R² score. Decision Tree
Regression achieved the lowest RMSE and the highest R² score, indicating better predictive
performance compared to Linear Regression and Ridge Regression. The comparison table
shows that Decision Tree Regression is the best-performing model among the tested models.
5. Conclusion :-
This project demonstrated the comparison of multiple machine learning models for house
price prediction. Among the tested models, Decision Tree Regression performed the best.
In future work, advanced models such as Random Forest and Gradient Boosting can be implemented to further improve prediction accuracy.
