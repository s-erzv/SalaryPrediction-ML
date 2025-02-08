Exploratory Data Analysis (EDA) is an essential step in any data science project, helping to uncover data patterns, detect anomalies, and gain insights before applying machine learning models. In this salary prediction project, EDA is used to analyze salary data, visualize trends, and ensure the dataset is clean for model training. The project employs multiple regression-based supervised learning techniques to predict salaries based on experience. Various models, including Linear Regression, Decision Tree, and Random Forest, are applied to evaluate their effectiveness in predicting salaries.

Goals:
1. Conduct EDA to explore data distributions and relationships.
2. Perform data preprocessing, including handling duplicates and missing values (this dataset contains no categorical variables).
3. Train and compare multiple regression models: Linear Regression, Decision Tree, and Random Forest.
4. Evaluate model performance using metrics like Mean Squared Error (MSE) and R² score.
5. Summarize findings and provide recommendations for selecting the best model.

Insights:
- Exploratory Data Analysis (EDA)
The dataset contains no missing or duplicate values, and preprocessing ensures it is ready for training. Initial visualizations confirm a positive correlation between experience and salary.

- Linear Regression Model
This model provides a basic yet interpretable approach to salary prediction but shows signs of underfitting, meaning it does not fully capture the complexity of the data. While generalization to new data is decent, accuracy remains limited.

- Decision Tree Model
The Decision Tree model achieves near-perfect performance on training data but significantly worsens on test data, indicating severe overfitting. This model memorizes training data rather than generalizing patterns.

- Random Forest Model
Compared to the Decision Tree, Random Forest reduces overfitting and offers better stability across training and testing datasets. While it still slightly overfits, it provides a more reliable salary prediction model.

Recommendations:
Selecting the Right Model
- Use Linear Regression for quick, interpretable results where moderate accuracy is acceptable.
- Choose Random Forest if higher accuracy is needed, as it balances prediction stability and generalization.
Enhancing Model Performance
- Apply hyperparameter tuning (e.g., adjusting tree depth in Decision Tree and Random Forest) to reduce overfitting.
- Regularly evaluate the model with new data to maintain its predictive power over time.
- Consider adding new features like job industry, location, or education level to enhance prediction accuracy.
- If possible, increase dataset size to improve model robustness and reduce variance.
