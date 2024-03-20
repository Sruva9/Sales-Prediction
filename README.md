# Sales-Prediction
**Problem Statement:**

The task is to predict sales based on advertising expenses across different channels (TV, Radio, and Newspaper). The dataset provided contains information about advertising expenses on these channels as well as corresponding sales figures. The goal is to develop a machine learning model that can accurately predict sales based on the advertising expenses.

**Analysis Steps:**

1. **Understanding the Dataset:**
   - The dataset contains information about advertising expenses on TV, Radio, and Newspaper, along with corresponding sales figures.
   - Check the structure of the dataset, including column names, data types, and any missing values.

2. **Data Preprocessing:**
   - Separate the features (advertising expenses) and the target variable (sales).
   - Split the dataset into training and testing sets to evaluate the model's performance.

3. **Model Selection and Training:**
   - Choose a suitable machine learning model for regression tasks. Here, a Linear Regression model is used due to its simplicity and interpretability.
   - Train the model using the training data.

4. **Model Evaluation:**
   - Make predictions on the testing set.
   - Evaluate the model's performance using Mean Squared Error (MSE), a common metric for regression tasks. Lower MSE indicates better performance.
   - Visualize the actual vs. predicted sales to visually inspect the model's performance. The points should ideally form a diagonal line.
   - Visualize the residuals (differences between actual and predicted sales) to check for any patterns or trends.

5. **Predictions:**
   - Use the trained model to make predictions for new data. In this case, predict sales for a hypothetical scenario with given advertising expenses on TV, Radio, and Newspaper.

6. **Conclusion:**
   - Summarize the findings and the model's performance.
   - Discuss any potential areas of improvement or further analysis.

By following these steps, we can develop and evaluate a machine learning model for sales prediction based on advertising expenses.
