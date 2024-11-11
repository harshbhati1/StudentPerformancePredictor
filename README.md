# Student Performance Prediction (Multiple Linear Regression)

## 🚀 Overview

This project uses **Multiple Linear Regression** to predict student performance based on several key factors. By analyzing data such as hours studied, previous academic scores, extracurricular activities, and sleep habits, the model provides insights to help students optimize their study habits for better academic results.

## 🧑‍💻 Features

- **Predicts student performance**: Using factors like hours studied, previous scores, extracurricular involvement, and more.
- **Visualizes relationships**: Shows how different study habits affect performance.
- **Insights for improvement**: Helps students and educators identify key areas to focus on for better academic success.

## 🔬 Methodology

### Data Preprocessing:
1. **Handling Categorical Data**: The 'Extracurricular Activities' column was converted from True/False to 0/1 for compatibility with the model.
2. **Normalization**: All numerical features were normalized to a range of 0 to 1 using **MinMaxScaler** to ensure the model learns effectively.
3. **Train-Test Split**: The dataset was divided into training and testing sets to evaluate the model’s performance.

### Model:
- We used **Multiple Linear Regression** from `scikit-learn` to train the model.
- Evaluated the model using performance metrics like:
  - **Mean Absolute Error (MAE)**
  - **Mean Squared Error (MSE)**
  - **Root Mean Squared Error (RMSE)**

### Model Evaluation:
- **Residuals Analysis**: We checked for randomness in the residuals to ensure the model was fitting the data well.
- **Predictions**: Visualized predictions against actual values to confirm the model's accuracy.

## 📊 Results

The model showed promising results:
- **Mean Absolute Error (MAE)**: 1.61
- **Mean Squared Error (MSE)**: 4.07
- **Root Mean Squared Error (RMSE)**: 2.02

These metrics indicate that the model's predictions are generally accurate, with an average error of about 1 performance point. The model performs well, and the residuals show no significant patterns, which means the model fits the data effectively.

### Key Insights:
- **Previous Scores** and **Hours Studied** were found to be the strongest predictors of student performance.
- The model helps identify how specific behaviors, like studying more or practicing question papers, can boost performance.

## 📦 Requirements

You’ll need the following Python libraries to run this project:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`


## 🏃‍♀️ How to Run

1. **Clone the repository:**
    ```bash
    git clone https://github.com/harshbhati1/StudentPerformancePredictor.git
    ```

2. **Navigate to the project folder:**
    ```bash
    cd StudentPerformancePredictor
    ```

3. **Run the notebook:**
    Open the notebook using Jupyter:
    ```bash
    jupyter notebook Notebook.ipynb
    ```

## 📊 Dataset

Download the dataset from Kaggle: [Student Performance Dataset](https://www.kaggle.com/datasets/nikhil7280/student-performance-multiple-linear-regression/code?datasetId=3462333)  
Place the dataset file (`Student_Performance.csv`) in the project folder.

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙌 Acknowledgments

Special thanks to Kaggle for providing the [Student Performance Dataset](https://www.kaggle.com/datasets/nikhil7280/student-performance-multiple-linear-regression/code?datasetId=3462333)
To install all the dependencies, run:

```bash
pip install -r requirements.txt


