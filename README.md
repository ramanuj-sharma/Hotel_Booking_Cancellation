# Hotel Booking Cancellation Prediction

## Overview

This project aims to predict hotel booking cancellations using various machine learning models. The analysis covers data cleaning, feature engineering, model training, and evaluation.

## Data Description

The dataset includes information on hotel bookings, with features such as:

- **Hotel:** Type of hotel (e.g., City Hotel, Resort Hotel)
- **Is Canceled:** Booking cancellation status
- **Lead Time:** Number of days between booking date and arrival date
- **ADR:** Average Daily Rate
- **Special Requests:** Number of special requests made

## Methodology

1. **Data Preprocessing:**
   - Handling missing values
   - Feature selection using Lasso regression

2. **Model Training:**
   - Models: Logistic Regression, Naive Bayes, Random Forest, Decision Tree, KNN
   - Evaluation using accuracy, precision, recall, F1-score, and ROC-AUC

3. **Visualization:**
   - ROC Curves to compare model performance

## Results

- **Best Model:** Random Forest with an accuracy of 85.5% and ROC-AUC of 0.93
- **Feature Importance:** Lead time and ADR were prominent in predicting cancellations


## How to Use

1. **Install Dependencies:**
   - Python 3.x
   - Required libraries: `pandas`, `numpy`, `scikit-learn`, `plotly`

2. **Run the Scripts:**
   - Jupyter Notebook or Python script in a suitable environment

3. **Input Your Data:**
   - Provide the dataset in CSV format with the expected columns

## Conclusion

The project demonstrates the use of machine learning to predict hotel booking cancellations effectively. Random Forest emerged as the most robust model, offering valuable insights for hotel management.

## Future Work

- **Hyperparameter Tuning:** Further refine model parameters for enhanced accuracy
- **Additional Features:** Include external data, such as weather or economic indicators
- **Real-time Prediction:** Deploy the model for live booking predictions