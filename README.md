🎬 Movie Rating Prediction – Machine Learning Project

📌 Project Overview
This project aims to predict IMDb ratings of Indian movies based on features like genre, director, and movie name.
It demonstrates how to handle categorical variables and apply regression models to predict continuous outcomes.
The dataset used includes real movie metadata with associated user ratings.

📊 Features Used
Genre: Type of movie (e.g., Action, Drama, Comedy)
Director: Person who directed the movie
Name: Title of the movie
Rating: Target variable (IMDb rating score)

🧠 Machine Learning Techniques
Data Cleaning: Removed rows with missing values to ensure model integrity.
Feature Encoding: Used Label Encoding for initial experiments.
Model Training: Trained using Linear Regression and Random Forest Regressor.
                Chose Random Forest for final predictions due to better accuracy on test data.

Model Evaluation:
Calculated Mean Squared Error (MSE) and R² Score to evaluate prediction accuracy.

📈 Data Visualization
Visualized rating distribution using histograms.
Analyzed most common genres and directors.
Box plots were used to compare ratings across genres and directors.

🛠️ Tools & Libraries
Python for scripting
Pandas and NumPy for data manipulation
Matplotlib and Seaborn for visualization
Scikit-learn for model building and evaluation
