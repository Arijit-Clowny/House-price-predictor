# 🏡 California House Price Prediction

A Machine Learning project that predicts median house values in California using **Linear Regression** and the California Housing Dataset. Built with Python, NumPy, Pandas, Scikit-learn, Matplotlib, and Seaborn.

The project explores the complete machine learning workflow, from data loading and exploratory analysis to model training, prediction, visualization, and performance evaluation.

## 📌 Project Overview

The objective of this project is to develop a Linear Regression model capable of predicting California house prices based on different housing and geographical features.

The project focuses on understanding how supervised machine learning works in practice, implementing a regression algorithm, and evaluating its predictive performance using standard regression metrics.

## 🎯 Objectives

- Understand and explore the California Housing Dataset.
- Perform data preparation and preprocessing.
- Implement Linear Regression using Scikit-learn.
- Train and test the model using a train-test split.
- Generate predictions on unseen data.
- Evaluate model performance using regression metrics.
- Visualize actual vs. predicted values and analyze residuals.
- Compare training and testing performance to understand generalization.

## 📊 Dataset

**California Housing Dataset**

The dataset contains information about housing districts in California, collected from the 1990 U.S. Census.

It includes the following eight input features:

| Feature | Description |
|---|---|
| MedInc | Median income in the block group |
| HouseAge | Median house age |
| AveRooms | Average number of rooms |
| AveBedrms | Average number of bedrooms |
| Population | Block group population |
| AveOccup | Average household occupancy |
| Latitude | Geographical latitude |
| Longitude | Geographical longitude |

**Target Variable:** `MedHouseVal` — Median house value.

The target is represented in units of $100,000. For example, a target value of 2.5 represents $250,000.

The dataset is accessed through Scikit-learn's `fetch_california_housing()` function.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| Jupyter Notebook | Development and experimentation |
| NumPy | Numerical computations |
| Pandas | Data manipulation and analysis |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Scikit-learn | Machine Learning and model evaluation |

## ⚙️ Project Workflow

The project follows these steps:

1. **Data Loading:** Import the California Housing Dataset using Scikit-learn.
2. **Data Exploration:** Examine the dataset, features, target variable, and statistical information.
3. **Data Preparation:** Separate independent variables (X) and the dependent variable (y).
4. **Train-Test Split:** Divide the dataset into training and testing subsets.
5. **Model Training:** Implement and train a Linear Regression model.
6. **Prediction:** Generate house price predictions using the testing dataset.
7. **Model Evaluation:** Calculate MAE, MSE, RMSE, and R² scores.
8. **Visualization:** Plot actual vs. predicted values and perform residual analysis.
9. **Performance Comparison:** Compare training and testing R² scores to evaluate generalization.

## 📈 Model Performance

The project uses four standard regression evaluation metrics.

### Testing Results

| Evaluation Metric | Result |
|---|---:|
| Mean Absolute Error (MAE) | 0.5332 |
| Mean Squared Error (MSE) | 0.5559 |
| Root Mean Squared Error (RMSE) | 0.7456 |
| R² Score | 0.5758 |

### Training vs. Testing Performance

| Dataset | R² Score |
|---|---:|
| Training | 0.6126 |
| Testing | 0.5758 |

The model achieves an R² score of approximately **57.58% on the testing dataset**.

The relatively small difference between training and testing R² scores suggests that the model generalizes reasonably consistently, although its predictive performance leaves room for improvement.

*Note: MAE and RMSE are expressed in the target variable's units ($100,000).*

## 📉 Data Visualization & Analysis

The project includes visualizations to understand the dataset and evaluate the model:

- Exploratory Data Analysis (EDA).
- Actual vs. Predicted House Prices.
- Residual Analysis.
- Training vs. Testing R² Comparison.

These visualizations help identify prediction errors, understand model behavior, and assess the quality of the regression model.

## 📁 Project Structure

```text
House-price-predictor/
│
├── notebooks/
│   └── task1_ml_linear_regression.ipynb
│
├── reports/
│   └── PDF Project Report
│
├── README.md
└── .gitignore
```

All machine learning implementation and experimentation are maintained inside the Jupyter Notebook.

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Arijit-Clowny/House-price-predictor.git
```

### 2. Navigate to the Project Directory

```bash
cd House-price-predictor
```

### 3. Install Dependencies

```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 5. Run the Notebook

Open the notebook inside the `notebooks/` directory and execute the cells sequentially.

The California Housing Dataset is retrieved through Scikit-learn when the notebook is executed.

## 🔮 Possible Future Improvements

Although this project focuses on Linear Regression, its performance could potentially be improved through:

- Feature engineering and feature selection.
- Experimentation with other regression algorithms.
- Hyperparameter tuning.
- Cross-validation.
- More advanced ensemble-based regression techniques.

These are potential extensions and are not part of the completed project deliverables.

## 📚 Key Learnings

Through this project, I gained practical experience in:

- Working with real-world datasets.
- Data exploration and preprocessing.
- Understanding supervised machine learning.
- Implementing Linear Regression.
- Using Scikit-learn for model development.
- Evaluating regression models using standard metrics.
- Visualizing predictions and analyzing residuals.
- Understanding the importance of model generalization.

## 👨‍💻 Author

**Arijit Shaw**

B.Tech Computer Science & Engineering  
Aspiring AI/ML and Data Science Engineer

- GitHub: [@Arijit-Clowny](https://github.com/Arijit-Clowny)

---

⭐ If you find this project interesting, consider giving the repository a star!
