**Dragon Real Estate - Price Predictor**

This machine learning project, "Dragon Real Estate - Price Predictor," is designed to predict housing prices based on various features. The project leverages the power of Python and key libraries to preprocess data, build a predictive model, and deploy it for real-world use.

**Tech Stack and Key Libraries:**
- **Python:** 
- **Pandas:** 
- **NumPy:** 
- **Matplotlib:** 
- **Scikit-learn:** 
- **Joblib:** 
- **Jupyter Notebooks:** 

**Key Steps:**
1. **Data Exploration and Analysis:** Pandas is utilized to explore the dataset, understand its structure, and perform statistical analysis. Matplotlib is employed to create visualizations that highlight key correlations between different features.

2. **Data Preprocessing:** Techniques such as train-test splitting, stratified sampling, and handling missing data are implemented to prepare the dataset for training the machine learning model. Attribute combinations are explored to enhance the model's predictive power.

3. **Feature Scaling:** Scikit-learn's preprocessing tools, specifically the `Pipeline` class, are used to create a streamlined process that includes imputing missing values and scaling numerical features.

4. **Model Selection and Training:** The project employs three types of regression models from Scikit-learn - Linear Regression, Decision Tree Regressor, and Random Forest Regressor. The Random Forest Regressor is chosen as the final model due to its better performance.

5. **Model Evaluation:** Evaluation metrics such as Mean Squared Error (MSE) and cross-validation scores are utilized to assess the model's performance. The project demonstrates the importance of using cross-validation for a more robust evaluation.

6. **Model Deployment:** The trained Random Forest Regressor model is saved using Joblib, allowing for easy deployment in real-world scenarios. The model is then tested on a separate test dataset to validate its predictive accuracy.

**Usage:**
The saved model (`Dragon.joblib`) can be loaded and utilized for predicting housing prices based on input features.

This project serves as a practical example of a real estate price prediction system.
