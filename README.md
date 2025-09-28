# house-price-prediction
A lightweight house price prediction model built entirely with NumPy, Pandas, and Matplotlib, designed for educational and practical purposes. This project demonstrates data-driven regression modeling without relying on scikit-learn or other machine learning libraries, making it perfect for understanding the core mechanics of feature engineering, polynomial regression, and gradient descent.

# Features
Automatic Feature Selection: Selects relevant features based on correlation with the target variable (Price).
Polynomial Regression: Supports linear, quadratic, and cubic feature interactions for better prediction accuracy.
Gradient Descent Optimization: Efficient parameter estimation without matrix inversion, scalable to larger datasets.
Feature Normalization: Automatically normalizes features to ensure stable gradient descent.
Automatic Polynomial Degree Selection: Chooses the best polynomial degree (1-3) based on Mean Squared Error (MSE).
Interactive Predictions: Predict the price of a new house by entering feature values, including handling binary categorical features (yes/no).
Visualization-:
  Actual vs Predicted prices
  Feature importance based on learned weights

# Usage
Train the model on your dataset (house_data.csv).
The notebook automatically selects features, polynomial degree, and trains the model using gradient descent.
Predict new house prices interactively or programmatically.
Visualize results and inspect feature importance.

# Tech Stack
Python 3.x
NumPy – for numerical computations
Pandas – for data handling and preprocessing
Matplotlib – for plotting and visualization

# Optional
Save trained model parameters using np.savez and create a Flask API for serving predictions in web applications.

💡 Highlights:
Purely library-light approach – perfect for learning the inner workings of regression and gradient descent.
Fully Jupyter Notebook–friendly, with step-by-step explanations.
Can be extended to API deployment or web integration easily.
