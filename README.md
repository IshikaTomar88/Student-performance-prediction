===============================

🎓 Student Performance Prediction

===============================

📌 Overview
-----------
This project focuses on predicting student academic performance using various machine learning models.
The notebook demonstrates the complete pipeline from data exploration, preprocessing, model training,
evaluation, and visualization of results. The objective is to identify key factors affecting student
performance and build models that can predict final exam scores.

📂 Dataset
----------
- Source: Kaggle Student Performance Dataset
- Features include demographic, social, and academic attributes.
- Target variable: G3 (final grade)

⚙️ Steps Followed
-----------------

1. Import Libraries
   - numpy, pandas → data manipulation
   - matplotlib, seaborn → data visualization
   - scikit-learn → preprocessing, regression models, metrics

2. Data Exploration (EDA)
   - Checked dataset structure, missing values, and summary statistics
   - Visualized distributions of categorical and numerical features
   - Analyzed correlations between features and the target variable
   - Example plot: Correlation Heatmap (saved in images/correlation_heatmap.png)

3. Data Preprocessing
   - Separated categorical and numerical features
   - Applied OneHotEncoding for categorical variables
   - Applied StandardScaler for numerical features
   - Used ColumnTransformer and Pipeline for cleaner preprocessing

4. Model Building
   - Trained and compared multiple regression models:
     * Linear Regression
     * Random Forest Regressor
     * Decision Tree Regressor
     * XGBoost Regressor

5. Model Evaluation
   - Metrics: R² Score, RMSE, MAE
   - Example plot: Model Comparison (saved in images/model_comparison.png)

6. Feature Importance
   - Explored which features have the most influence on student performance
   - Example plot: Feature Importance (saved in images/feature_importance.png)

📊 Results
----------
- Random Forest achieved the best performance with high R² and low RMSE.
- Study time, absences, parental education, and prior grades strongly influenced final grades.
- Simpler models like Linear Regression worked but underperformed compared to ensemble methods.

🚀 Future Improvements
-----------------------
- Hyperparameter tuning for better accuracy
- Use deep learning models (Neural Networks) for comparison
- Extend dataset with more socio-economic and behavioral features

📦 How to Run
-------------
1. Clone the repo and install requirements:
   pip install -r requirements.txt

2. Run the notebook:
   jupyter notebook Student_Performance_Prediction.ipynb

3. Execute all cells to preprocess data, train models, and generate plots.

🙌 Acknowledgments
------------------
- Dataset sourced from Kaggle contributors
- Inspired by the need to improve educational outcomes using data science
