# EstateValuator 
This project aims to develop a machine learning model capable of predicting real estate prices based on specific features such as square footage, the number of bedrooms, and the number of bathrooms. The model leverages advanced data preprocessing techniques and machine learning algorithms to deliver accurate predictions, aiding potential buyers, sellers, and real estate professionals in making informed decisions.

**Key Features:**

1.  **Data Collection and Preprocessing:**
    
    -   **Data Sources:** Collected data from various real estate listings and public records.
        
    -   **Cleaning:** Performed data cleaning to handle missing values, outliers, and inconsistencies.
        
    -   **Encoding:** Used One-Hot Encoding to convert categorical variables into a numerical format suitable for machine learning algorithms.
        
2.  **Feature Selection:**
    
    -   **Primary Features:** Square footage, number of bedrooms, and number of bathrooms were selected as the primary predictors of house prices.
        
3.  **Model Selection and Training:**
    
    -   **Algorithm:** Employed the Random Forest Regressor from Scikit-Learn, a powerful ensemble learning method that combines multiple decision trees to improve predictive accuracy and control overfitting.
        
    -   **Training:** Split the dataset into training and testing sets to evaluate the model's performance. Trained the model on the training set and fine-tuned the hyperparameters to optimize performance.
        
4.  **Evaluation:**
    
    -   **Metrics:** Used Mean Squared Error (MSE) and R-squared (R²) as the primary metrics for evaluating the model's performance.
        
    -   **Results:** The model demonstrated high accuracy in predicting house prices, with a strong correlation between the predicted and actual values.
        

**Technologies and Tools:**

-   **Programming Language:** Python
    
-   **Libraries:** Scikit-Learn, Pandas, NumPy, Matplotlib
    
-   **Data Preprocessing:** One-Hot Encoding, Data Cleaning
    
-   **Model:** Random Forest Regressor
    

**Conclusion:** The real estate price prediction model successfully predicts house prices based on square footage and the number of bedrooms and bathrooms, providing valuable insights for stakeholders in the real estate market. This project showcases the effective use of data preprocessing and machine learning techniques to solve real-world problems.
