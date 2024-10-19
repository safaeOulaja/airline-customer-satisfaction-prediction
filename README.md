# Airline Customers Satisfaction Detection

This project aims to predict passenger satisfaction with airline services based on various factors related to their flight experience. The dataset includes information about airline passengers, their flights, and ratings on various aspects such as cleanliness, comfort, service, etc.

## Problem Definition
The goal is to build a predictive model that accurately classifies passenger satisfaction levels (e.g., satisfied or dissatisfied).

## Dataset
The dataset contains the following features:
- **Numerical**: Age, Flight Distance, Departure Delay, Arrival Delay, etc.
- **Categorical**: Gender, Customer Type, Type of Travel, Class, etc.

## Data Preprocessing
- Handling missing values
- Detecting and treating outliers
- Feature engineering (e.g., creating new features like Total_Delay)

## Models Used
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- Neural Network
- k-Nearest Neighbors (k-NN)

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1 Score

## Results
The Random Forest model achieved the highest accuracy of 81%.

## How to Run
1. Clone the repository
   ```bash
   git clone https://github.com/safaeOulaja/airline-customer-satisfaction-prediction.git
   ```
2. Install the required libraries
   ```bash
   pip install scikit-learn seaborn matplotlib numpy scikit-plot
   ```
3. Run the Jupyter notebook
   ```bash
   jupyter notebook
   ```

## Conclusion
This project demonstrates the application of various machine learning models to predict airline customer satisfaction, with Random Forest providing the best performance.
