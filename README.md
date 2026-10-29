# ⚡ Electricity Theft Detection Using Machine Learning

An intelligent Machine Learning-based system designed to detect electricity theft and identify suspicious electricity consumption patterns using historical electricity consumption data.

## 📌 Project Overview

Electricity theft is a major challenge for power distribution companies. It causes financial losses, affects power distribution efficiency, and creates difficulties in accurate energy billing.

This project uses Machine Learning techniques to analyze electricity consumption patterns and classify consumers as **Normal** or **Potential Electricity Thieves**.

The objective is to improve electricity theft detection through data analysis, predictive modeling, and machine learning algorithms.

## 🎯 Objectives

- Detect abnormal electricity consumption patterns.
- Identify potential electricity theft using ML algorithms.
- Reduce manual inspection efforts.
- Compare different machine learning models.
- Evaluate model performance using standard evaluation metrics.
- Support smarter and more efficient electricity distribution.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| Pandas | Data manipulation |
| NumPy | Numerical computations |
| Scikit-learn | Machine Learning |
| XGBoost | Gradient boosting model |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Jupyter Notebook | Model development and experimentation |

## 📊 Dataset

**Dataset:** State Grid Corporation of China (SGCC) Electricity Consumption Dataset. and trying for indian dataset


The dataset contains historical electricity consumption records used to analyze consumer behavior and identify irregular consumption patterns.

Dataset preprocessing includes:
- Handling missing values.
- Data cleaning and transformation.
- Feature engineering.
- Data normalization and preparation.
- Training and testing data separation.

## 🤖 Machine Learning Algorithms

The project explores the following algorithms:

1. **Random Forest** – Ensemble learning algorithm used for classification.
2. **XGBoost** – Gradient boosting algorithm for effective classification.
3. **Deep Neural Network (DNN)** – Neural network-based approach for learning complex consumption patterns.
4. **Isolation Forest** – Anomaly detection algorithm for identifying unusual consumption behavior.

## ⚙️ Project Workflow

1. Data Collection
2. Data Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Model Training
6. Model Evaluation
7. Electricity Theft Prediction

## 📈 Model Evaluation Metrics

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score

These metrics help compare model performance and understand how effectively the system identifies potential electricity theft.

## 🚀 Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/keshavagg-dev/Electricity-theft-detection-using-ML.git
```

### 2. Navigate to the Project Directory

```bash
cd Electricity-theft-detection-using-ML
```

### 3. Create a Virtual Environment (Optional)

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

### 5. Run the Project

Open the project notebooks in Jupyter Notebook:

```bash
jupyter notebook
```

Run the relevant notebook cells in sequence. If the project includes a separate application entry point, run it according to its instructions.

## 📂 Project Structure

```text
Electricity-theft-detection-using-ML/
│
├── electricity-theft-detection-main/
│   ├── Dataset/
│   ├── Notebooks/
│   ├── Models/
│   ├── Source Code/
│   └── README.md
│
├── requirements.txt
└── README.md
```

*Note: The folder names above illustrate an example structure. Adjust them to match the actual repository files.*

## 🔮 Future Enhancements

- Integration with real-time smart meter data.
- Improved detection using advanced deep learning techniques.
- Integration of explainable AI (XAI).
- Development of an interactive monitoring dashboard.
- Testing with more region-specific electricity consumption datasets.
- Deployment as a web-based application.

## 👨‍💻 Author

**Keshav Aggarwal and Aman Sharma**

GitHub: [@keshavagg-dev](https://github.com/keshavagg-dev)

## 📜 License

This project is developed for educational and research purposes.

---

⭐ If you find this project interesting, consider giving the repository a star!

**Electricity Theft Detection Using Machine Learning — Towards Smarter and More Efficient Power Distribution.**
