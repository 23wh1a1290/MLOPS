# 🏠 House Price Prediction using MLOps

## 📌 Project Overview

House Price Prediction using MLOps is a Machine Learning regression project that predicts house rental prices based on various property-related features.

The project uses a NoBroker housing dataset and applies data preprocessing, Exploratory Data Analysis (EDA), and multiple regression algorithms to identify a suitable prediction model.

It also incorporates MLflow concepts for experiment tracking and reproducibility.

## 🎯 Objectives

- Analyze housing data and understand important property features.
- Perform data cleaning and preprocessing.
- Handle missing numerical and categorical values.
- Apply Exploratory Data Analysis and data visualization.
- Build and compare multiple Machine Learning regression models.
- Evaluate model performance using different regression metrics.
- Support experiment tracking using MLflow.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming language |
| Pandas | Data manipulation and analysis |
| NumPy | Numerical operations |
| Scikit-learn | Machine Learning and preprocessing |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| XGBoost | Gradient boosting regression |
| MLflow | Experiment tracking |

## 📂 Dataset

The project uses a cleaned NoBroker housing dataset in CSV format.

The dataset contains property-related attributes that help predict rental prices.

Examples of features include:
- Location
- Property area
- Number of bedrooms
- Furnishing status
- Other available property attributes

**Target Variable:** House Rental Price.

## 🔍 Exploratory Data Analysis (EDA)

EDA is performed to understand the dataset and identify patterns before model training.

The following operations are performed:

- Dataset inspection using `info()` and `head()`.
- Statistical analysis using `describe()`.
- Identification of missing values.
- Duplicate record checking.
- Numerical feature distribution using histograms.
- Correlation analysis using heatmaps.
- Outlier identification using boxplots.

## 🧹 Data Preprocessing

The following preprocessing techniques are implemented:

1. Removal of columns containing entirely missing values.
2. Mean imputation for numerical features.
3. Most-frequent imputation for categorical features.
4. One-Hot Encoding to convert categorical features into numerical representations.
5. ColumnTransformer to apply different preprocessing techniques to different feature types.
6. Scikit-learn Pipeline to combine preprocessing and model training.

## 🤖 Machine Learning Algorithms

Seven regression algorithms are implemented and compared:

1. Linear Regression
2. Ridge Regression
3. Lasso Regression
4. Decision Tree Regressor
5. Random Forest Regressor
6. Support Vector Regressor (SVR)
7. XGBoost Regressor

The models are trained and evaluated using an 80:20 train-test split.

## 📊 Model Evaluation

The models are evaluated using the following metrics:

| Metric | Description |
|---|---|
| R² Score | Measures how well the model explains variations in the target |
| MAE | Measures average absolute prediction error |
| MAPE | Measures average percentage prediction error |
| Training Time | Measures model execution time |

The evaluation results are stored in a Pandas DataFrame and sorted based on MAE to compare model performance.

## ⚙️ Project Workflow

1. Dataset Collection
2. Data Loading and Inspection
3. Exploratory Data Analysis
4. Data Cleaning and Preprocessing
5. Feature Transformation
6. Train-Test Splitting
7. Regression Model Training
8. Model Performance Evaluation
9. Experiment Tracking using MLflow

## 📁 Project Structure

```text
House_Price_Prediction/
│
├── data/
│   └── nobroker_cleaned_data.csv
│
├── notebooks/
│   ├── EDA.ipynb
│   └── Model_Training.ipynb
│
├── README.md
└── requirements.txt
```

*Note: Adjust the folder structure above to match your actual GitHub repository.*

## 🚀 Installation and Execution

### 1. Clone the Repository

```bash
git clone https://github.com/23wh1a1290/MLOPS.git
```

### 2. Navigate to the Project Directory

```bash
cd MLOPS
```

### 3. Install Dependencies

```bash
pip install pandas numpy scikit-learn matplotlib seaborn xgboost mlflow
```

Alternatively:

```bash
pip install -r requirements.txt
```

### 4. Load the Dataset

Place the cleaned NoBroker CSV dataset in the appropriate directory and update the dataset path in the Python code.

### 5. Run the Project

Open the Jupyter Notebook or Google Colab notebook and execute the cells to perform EDA, preprocessing, model training and evaluation.

## 📈 Expected Outcome

The project generates a comparative evaluation summary of seven regression algorithms.

The model with the most suitable evaluation performance can be selected for predicting house rental prices.

## 🔮 Future Enhancements

- Implement hyperparameter tuning to improve prediction performance.
- Develop a user-friendly web interface for rental price prediction.
- Deploy the trained model using Flask or FastAPI.
- Integrate automated model training and evaluation pipelines.
- Enhance MLflow experiment tracking and model version management.
- Implement model monitoring to track prediction performance.

## 👩‍💻 Author

**Deepika Nadimidoddi**

- GitHub: [23wh1a1290](https://github.com/23wh1a1290)
- Project: House Price Prediction using MLOps

---

⭐ If you find this project interesting, feel free to explore the repository!
