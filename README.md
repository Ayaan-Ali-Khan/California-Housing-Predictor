# California Housing Prediction Model
**Project Overview**:
Built a regression model to predict median housing prices in California districts using the California Housing dataset (20,640 samples, 8 features including location, population, median income).

Key Stages Implemented:

📊 **Data Exploration & Visualization**
- Performed exploratory data analysis (EDA) to understand feature distributions and correlations
- Visualized geographic data, identified patterns in housing prices across California
- Analyzed feature relationships using correlation matrices and scatter plots

🔧**Data Preprocessing**
- Handled missing values using appropriate imputation strategies
- Feature engineering: created new features (rooms per household, population per household)
- Feature scaling: standardization and normalization for different algorithms
- Train-test split with stratified sampling to ensure representative data distribution

🤖 **Model Development & Evaluation**
- Trained multiple regression models: Linear Regression, Decision Trees, Random Forest
- Implemented cross-validation for robust performance evaluation
- Compared models using metrics: RMSE, MAE, R² score
- Fine-tuned best performing model using GridSearchCV for hyperparameter optimization
- Evaluated final model on test set to assess generalization

📦 **Pipeline Development**
- Built complete scikit-learn Pipeline integrating preprocessing and model training
- Implemented custom transformers for feature engineering
- Ensured reproducible and maintainable code structure

This project has the complete ML workflow beyond just model training - data exploration, feature engineering, model selection, evaluation strategies, and building production-ready pipelines.

Technologies: Python, Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook
Reference: Chapter 2 - "Hands-On Machine Learning with Scikit-Learn, Keras & TensorFlow" by Aurélien Géron
