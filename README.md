# Water Quality Prediction Using Machine Learning

## Project Overview
The Water Quality Prediction project uses machine learning classification algorithms to predict whether a water sample is classified as **Safe** or **Unsafe** based on its water-quality parameters.

The main objective is to demonstrate how machine learning can support preliminary water-quality classification.

## Dataset Description
The dataset contains 100,800 records with five columns.

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

## Machine Learning Algorithms
1. **Logistic Regression** – A supervised classification algorithm used for binary classification.
2. **Gaussian Naive Bayes** – A probabilistic classification algorithm based on Bayes' theorem, suitable for continuous numerical features.

## Project Workflow
1. Dataset loading
2. Data exploration and analysis
3. Missing-value and duplicate checking
4. Data visualization
5. Label encoding
6. Train-test splitting (80:20)
7. Feature scaling for Logistic Regression
8. Model training
9. Model evaluation
10. Water-quality prediction

## Evaluation Metrics
The models are evaluated using:
- Accuracy Score
- Confusion Matrix
- Classification Report
  - Precision
  - Recall
  - F1-score

## Project Files
- `Water_Quality_Prediction.ipynb` – Jupyter Notebook containing the complete implementation.
- `water_quality_dataset1.csv` – Dataset used for training and testing.
- `README.md` – Project documentation.

## How to Run the Project

1. Clone this repository:

   ```bash
   git clone https://github.com/Gayathri14-07/water-quality-prediction.git
   ```

2. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```

3. Open Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

4. Open `Water_Quality_Prediction.ipynb` and run the cells.

## Conclusion
This project demonstrates the application of Logistic Regression and Gaussian Naive Bayes for water-quality classification. It provides a basic machine learning approach to predicting water samples as Safe or Unsafe based on the dataset.

**Disclaimer:** The predictions depend on the dataset's labels and should not be treated as certification of drinking-water safety. Laboratory testing is necessary to establish whether water is safe to drink.
