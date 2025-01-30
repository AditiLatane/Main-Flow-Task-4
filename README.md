Dataset Source : https://www.kaggle.com/datasets/zafarali27/house-price-prediction-dataset?resource=download
        
Steps :

1. Load and analyse dataset
    - Check for missing values and handle them appropriately.
    - Analyze distributions of numerical variables (e.g., Size, Price).
    - Identify potential outliers that might skew results.
    
    
    
2. Data Preprocessing
    - Normalize Numerical Data:
        - Robust Scaling uses the median and IQR (Interquartile Range) to scale data, making it robust to outliers.
        - Formula:𝑋′=(𝑋−Median)/IQR
    - Encode Categorical Features:
        - Convert Locationand Condition into numerical values using Label Encoding for ordinal categories.
            
            
            
3. Feature Selection
    - Use correlation analysis to identify relationships between features and the target variable (Price).
    - Consider removing low-impact predictors to improve model performance.
        
        
4. Model Training
    - Train-Test Split
    - Train a Linear Regression Model
    
    
5. Model Evaluation
    - The model exhibits moderate predictive power, as evidenced by the R-squared score of 0.41.
    - The MAE and MSE values suggest that the model's predictions have an average error of around 0.44 units and 0.29 
      squared units, respectively.
      
6. Prediction
    - Difference between Predicted and Actual prices is almost negligible

Task 1 Link : https://github.com/AditiLatane/Main-Flow-Task-1.git
