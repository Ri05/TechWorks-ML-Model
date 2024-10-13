# TechWorks-ML-Model
The goal is to create a machine learning model that predicts the salaries of new employees at TechWork Consulting, a company that helps businesses find skilled IT professionals quickly and effectively.

### Model Comparison and Performance

In this project, we have implemented and compared several machine learning models to predict salaries based on various factors. The models were run and evaluated in the Jupyter Notebook available at [this link](https://github.com/Ri05/TechWorks-ML-Model/blob/main/Project_1_ML.ipynb).

#### Models Implemented

- **Linear Regression**: A basic model that predicts salaries based on simple linear relationships between the predictors and the outcome variable.
- **Multiple Regression**: This model handles multiple predictor variables simultaneously, allowing for a more comprehensive analysis of how different factors influence salaries.
- **Ridge Regression**: A regularization technique that adds penalties for large coefficients to avoid overfitting, ensuring that the model generalizes well to new data.
- **Lasso Regression**: Similar to Ridge Regression but uses L1 regularization, which can set some coefficients to zero, effectively performing feature selection.
- **Decision Tree Regression**: Captures complex interactions between features by recursively partitioning data into smaller subsets based on feature values.
- **Ensemble Methods**
  - **Bagging**: Combines multiple models (like Random Forest) to improve accuracy and stability by averaging out individual model errors.
  - **Boosting**: Sequentially improves models by focusing on previous mistakes (including Gradient Boosting and AdaBoost).

### Key Findings

After running these models, we observed the following key findings:

- The highest R² value was achieved using **Bagging**. This indicates that the ensemble method of combining multiple models significantly improved the predictive power of our salary prediction model. The R² value measures how well the model explains the variability in the data, and a higher value suggests better fit and predictive accuracy.

### Conclusion

The results from our analysis suggest that **Bagging** is the most effective approach for predicting salaries in this dataset. By leveraging the strengths of multiple models through ensemble learning, we were able to achieve a higher R² value compared to other individual models. This highlights the importance of using ensemble methods when dealing with complex datasets where single models may not capture all nuances.

For detailed implementation and results, please refer to the Jupyter Notebook available at [this link](https://github.com/Ri05/TechWorks-ML-Model/blob/main/Project_1_ML.ipynb).
