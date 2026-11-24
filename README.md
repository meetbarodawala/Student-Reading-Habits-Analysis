# 📊 Student Reading Habits Analysis

An end-to-end **Data Analytics and Machine Learning project** developed using Python to explore student reading behaviour, identify patterns in reading performance, and build predictive models for reading scores and reading levels.

The project uses the `student_reading_habits.csv` dataset and demonstrates a structured analytical workflow covering data exploration, cleaning, statistical analysis, predictive modelling, and visualization.

## 🎯 Project Objectives

- Understand student reading and study behaviour.
- Explore relationships between study habits and reading performance.
- Identify missing values and potential outliers.
- Apply statistical techniques to analyse data distribution.
- Predict reading scores using Linear Regression.
- Classify reading levels using Logistic Regression.
- Evaluate model performance using appropriate metrics.

## 🛠️ Technologies & Libraries

| Technology | Purpose |
|---|---|
| Python 3.x | Core programming language |
| Pandas | Data manipulation and analysis |
| NumPy | Numerical computing |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Scikit-learn | Machine learning and model evaluation |
| Jupyter Notebook | Interactive analysis |

## 📂 Project Workflow

The project is organized into eleven analytical tasks:

1. **Data Understanding** — Load and inspect the dataset.
2. **Exploratory Data Analysis (EDA)** — Histograms, boxplots, scatter plots, correlation heatmaps and pair plots.
3. **Data Cleaning** — Handle missing values and identify outliers.
4. **Spread of Data** — Analyse mean, median, standard deviation, skewness and kurtosis.
5. **EDA Automation** — Develop a reusable `eda_summary()` function.
6. **Regression Analysis** — Examine covariance and correlation between study hours and reading scores.
7. **Supervised Learning** — Train a Linear Regression model to predict reading scores.
8. **Model Generalization** — Compare training and testing R² scores to investigate overfitting and underfitting.
9. **Classification** — Use Logistic Regression to predict reading-level categories.
10. **Model Evaluation** — Evaluate classification using accuracy, precision, recall, F1-score and confusion matrix.
11. **Data Visualization** — Present analytical findings through visualizations.

## 🤖 Machine Learning Models

### 1. Linear Regression

Used to predict student reading scores based on study-related data.

- Training and testing split: 80% / 20%
- Evaluation: R², Mean Absolute Error (MAE), Mean Squared Error (MSE)

### 2. Logistic Regression

Used to classify students into reading-level categories.

- Classification target: `Reading_Level`
- Evaluation: Accuracy, precision, recall, F1-score and confusion matrix.

## 📈 Key Findings

According to the project analysis:

- Positive relationships were observed between study hours, books read per month, and reading scores.
- Missing values were handled using mean imputation.
- A reusable EDA function was developed to automate exploratory analysis.
- Linear Regression was trained to predict reading scores.
- Logistic Regression was used to classify reading levels.
- Model performance and generalization were assessed using evaluation metrics.

## 🚀 Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook
- pip

### Install dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### Run the project

1. Clone this repository.
2. Open the project directory.
3. Launch Jupyter Notebook:

```bash
jupyter notebook
```

4. Open the project `.ipynb` notebook.
5. Make sure `student_reading_habits.csv` is available at the dataset path used in the notebook.
6. Run the notebook cells in sequence.

## 📚 Documentation

The detailed academic project report explains the objectives, methodology, eleven analytical tasks, implementation, model evaluation, visualizations and conclusions.

## 🔮 Future Scope

- Explore additional machine learning algorithms.
- Improve predictive model performance.
- Develop interactive dashboards for analytical results.
- Extend the analysis with additional student behaviour features.
- Explore more advanced predictive analytics techniques.

## 👨‍💻 Project Information

**Project:** Student Reading Habits Analysis  
**Course:** Data Analytics using Python  
**Academic Programme:** Bachelor of Computer Applications (BCA)  
**Language:** Python

---

*This project demonstrates the application of Python-based data analytics, statistical methods, data visualization, and supervised machine learning to an educational dataset.*
