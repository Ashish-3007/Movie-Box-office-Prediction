# Movie-Box-office-Prediction

🎬 Movie Revenue Prediction using Machine Learning

This project applies machine learning techniques to predict the box office revenue of movies based on structured metadata such as budget, genres, production companies, release year, and runtime. Using the Random Forest Regressor, the model demonstrates how data-driven insights can aid in forecasting financial success in the film industry.

📌 Key Features

Data Preprocessing:

Handled missing values, duplicates, and outliers.

Converted categorical variables (e.g., genres, production companies) using encoding.

Normalized numerical features such as budget and runtime.

Feature Engineering:

Extracted useful features from release dates (year, month, day).

Aggregated genre and language metadata into machine-readable formats.

Created new variables for improving prediction accuracy.

Modeling & Evaluation:

Implemented Random Forest Regressor for predicting revenue.

Hyperparameter tuning with GridSearchCV for optimization.

Evaluated performance using R² Score, RMSE, and MAE.

Visualization:

Revenue distribution analysis across genres, budgets, and release years.

Feature importance visualization to understand model decisions.

⚙️ Tech Stack

Language: Python 3.x

Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

Model: Random Forest Regressor (Scikit-learn)

Data Source: Public movie metadata dataset (structured CSV format)

🚀 Results

Achieved strong prediction accuracy with R² score > 0.75.

Identified budget and release year as primary drivers of box office success.

Provided explainable insights through feature importance ranking.

📂 Future Enhancements

Integration of NLP-based sentiment analysis on reviews and social media.

Use of deep learning (LSTMs/Transformers) for dynamic trend forecasting.

Expanding dataset with international box office data for global generalization.
