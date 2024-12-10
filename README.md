### Task  
In this task, two primary goals are tackled: (1) training linear regression models to predict car selling prices, and (2) assessing data ethics issues. Questions 1–6 address the prediction model, while Question 7 concerns ethical data practices.

### Data Used  
The dataset comprises cleaned car sales data, including columns like year, km driven, fuel type, seller type, owner, and selling price. These variables are used to build predictive models for car resale values.

### Algorithms Applied  
Linear regression models are built by selecting features based on correlation analysis. Two cases of training/testing data are examined: one using 10% and the other using 90% of the dataset. The impact of feature selection (most vs. least correlated features) and training set size on model performance is evaluated.

### Deployment/Execution  
The dataset is processed with pandas, and linear regression models are trained using scikit-learn. Models are evaluated on metrics like Mean Squared Error (MSE) and Root Mean Squared Error (RMSE), with visualisations created via matplotlib to observe actual vs. predicted results.

### Key Takeaways  
- **Correlations:** "Year" has the strongest correlation with selling price, while "Fuel Type" has the weakest. These correlations influence model accuracy.
- **Model Performance:** Larger training sets yield better results in terms of prediction accuracy, but feature selection (more correlated features) also plays a critical role in improving model performance.
- **Ethical Concerns:** Data ethics analysis revealed that infographics, though technically accurate, can be manipulated to push specific agendas by selectively highlighting different metrics.
