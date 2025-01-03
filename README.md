# CROP EXPORT VALUE PREDICTION
## Project Overview
This project aims to predict the export value of crops three years into the future using machine learning. Leveraging historical agricultural and economic data from FAOSTAT, the model employs a multi-layer perceptron (MLP) architecture to provide accurate predictions. By enabling better forecasting, this project supports decision-making for policymakers, traders, and agricultural planners.

## Features
- Historical data pre-processing from FAOSTAT.
- Custom multi-layer perceptron (MLP) model implemented for regression.
- Prediction of export values up to three years ahead.
- Visualizations for data insights and model performance evaluation.

---

## Technologies Used
- **Programming Language:** Python
- **Libraries:**
  - Pandas: Data manipulation and analysis
  - NumPy: Numerical computations
  - Scikit-learn: Data pre-processing and evaluation metrics
  - TensorFlow/Keras: Building and training the MLP model
  - Matplotlib & Seaborn: Data visualization

---

## Dataset
- **Source:** FAOSTAT (Food and Agriculture Organization of the United Nations)
- **Data Attributes:**
  - Crop type
  - Export values
  - Time series data
  - Geographical information

---

## Model Architecture
- The model consists of:
  - Input layer: Processes multiple features.
  - Hidden layers: Fully connected layers with ReLU activation.
  - Output layer: Produces a single continuous value (export value).
- Optimization: Adam optimizer with Mean Squared Error (MSE) as the loss function.
