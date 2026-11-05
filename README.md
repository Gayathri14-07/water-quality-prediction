# Water Quality Prediction Using Machine Learning

## Project Overview
This project uses Machine Learning to predict whether a water sample is classified as **Safe** or **Unsafe** based on its water-quality parameters.

The project uses Logistic Regression, a supervised machine learning classification algorithm, for binary classification.

## Dataset Description
The dataset contains 100,800 records and five columns.

**Input Features:**
- pH
- TDS (Total Dissolved Solids) – ppm
- Turbidity – NTU
- Temperature – °C

**Target Variable:**
- Label – Safe / Unsafe

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Machine Learning Algorithm
**Logistic Regression**

Logistic Regression is a supervised classification algorithm used to predict one of two classes: Safe or Unsafe.

## Project Workflow
1. Dataset loading
2. Data exploration and analysis
3. Missing-value and duplicate checking
4. Data visualization, including line plots
5. Label encoding
6. Train-test splitting (80:20)
7. Feature scaling using StandardScaler
8. Logistic Regression model training
9. Model evaluation
10. Water-quality prediction

## Evaluation Metrics
The model is evaluated using:
- Accuracy Score
- Confusion Matrix
- Classification Report
  - Precision
  - Recall
  - F1-score

## Project Files
- `Water_Quality_Prediction.ipynb` – Complete project implementation.
- `water_quality_dataset1.csv` – Dataset used for training and testing.
- `README.md` – Project documentation.

## How to Run the Project

Clone the repository:

```bash
git clone https://github.com/Gayathri14-07/water-quality-prediction.git
```

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

Start Jupyter Notebook:

```bash
jupyter notebook
```

Open `Water_Quality_Prediction.ipynb` and run the cells.

## Conclusion
This project demonstrates how Logistic Regression can be applied to classify water samples as Safe or Unsafe using selected water-quality parameters.

**Disclaimer:** Predictions depend on the dataset labels and are not a substitute for laboratory testing to establish drinking-water safety.
