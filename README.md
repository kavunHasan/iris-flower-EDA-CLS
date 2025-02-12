# Iris Flower Classification Project

## 🌸 Project Overview
This project focuses on classifying iris flowers into three species: *setosa*, *versicolor*, and *virginica* using machine learning algorithms. The dataset used is the famous **Iris Dataset**, which contains measurements of sepal and petal length and width.

## 📊 Dataset Information
- **Features:**
  - Sepal length (cm)
  - Sepal width (cm)
  - Petal length (cm)
  - Petal width (cm)
- **Target Classes:**
  - 0: Setosa
  - 1: Versicolor
  - 2: Virginica

## 🚀 Project Structure
```
├── iris_dataset_analysis.ipynb
├── requirements.txt
├── README.md
├── .gitignore
└── myvenv/ (ignored)
```

## 🔍 Exploratory Data Analysis (EDA)
- Data loading and inspection
- Checking for missing values
- Visualizations with **Seaborn** and **Matplotlib**
  - Pairplots
  - Correlation heatmaps

## 🤖 Machine Learning Model
- **Algorithm Used:** K-Nearest Neighbors (KNN)
- **Steps:**
  - Data splitting (train/test)
  - Model training
  - Evaluation using accuracy score, confusion matrix, and classification report

## 📈 Results
- **Model Accuracy:** ~100% (on test data)
- Detailed classification report with precision, recall, and F1-score.

## ⚙️ Installation & Usage
1. Clone the repository:
   ```bash
   git clone <repository-link>
   cd iris-flower-classification
   ```
2. Set up a virtual environment:
   ```bash
   python -m venv myvenv
   myvenv\Scripts\activate  # For Windows
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

## 📦 Requirements
```bash
numpy
pandas
matplotlib
seaborn
scikit-learn
```





