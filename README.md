<div align="center">

# 🌍 Geopolitical Events & Gold Price-Based Exchange Rate Prediction

### Predicting Foreign Exchange Rates using Machine Learning, NLP, Geopolitical Events, and Gold Prices

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-Data_Analysis-green)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine_Learning-orange)
![NLP](https://img.shields.io/badge/NLP-TF--IDF-red)
![License](https://img.shields.io/badge/License-MIT-success)

</div>

---

# 📖 Overview

This project presents an end-to-end Machine Learning pipeline that predicts foreign exchange rates by integrating:

- 🌍 Geopolitical conflict events
- 📰 Textual event descriptions
- 🪙 Gold prices
- 📈 Historical exchange rate data

The system combines structured numerical features with Natural Language Processing (NLP) techniques to capture the influence of geopolitical events on currency markets.

The project demonstrates the complete data science workflow, from raw datasets to predictive modeling.

---

# ✨ Features

- Data Loading
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Text Processing
- TF-IDF Tokenization
- Gold Price Integration
- Multi-output Exchange Rate Prediction
- Multiple Machine Learning Models
- Model Evaluation
- Feature Importance Analysis
- Prediction API Function
- Improved Model Pipeline

---

# 🏗 Project Workflow

```text
Raw Datasets
      │
      ▼
Data Cleaning
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Feature Engineering
      │
      ▼
TF-IDF Tokenization
      │
      ▼
Dataset Integration
      │
      ▼
Train/Test Split
      │
      ▼
Model Training
      │
      ▼
Model Comparison
      │
      ▼
Performance Evaluation
      │
      ▼
Prediction
```

---

# 📂 Project Structure

```
.
│
├── Notebook.ipynb
├── merged_aggregate.csv
├── Foreign_Exchange_Rates.csv
├── gdelt_conflict_1_0.csv
├── README.md
└── models/
```

---

# 📊 Dataset

The project utilizes three major data sources.

## 1. Geopolitical Events

Contains:

- Event descriptions
- Goldstein Scale
- Event statistics
- Year
- Sentiment indicators

---

## 2. Exchange Rates

Historical foreign exchange rates for multiple currencies.

---

## 3. Gold Prices

Historical (or simulated) gold prices used as an additional economic indicator.

---

# 🧠 Machine Learning Pipeline

The notebook performs:

## Data Preprocessing

- Missing value handling
- Feature selection
- Data normalization
- Encoding
- Dataset merging

---

## NLP Processing

Textual geopolitical events are transformed using:

- TF-IDF Vectorization

Keyword extraction includes concepts such as:

- war
- conflict
- military
- peace
- sanctions
- economy

---

## Feature Engineering

The project creates additional features including:

- Event Description Length
- Word Count
- Sentiment
- Gold Price
- Goldstein Scale
- Interaction Features

---

# 🤖 Machine Learning Models

Several regression algorithms are trained and compared.

Including:

- Random Forest Regressor
- Gradient Boosting Regressor
- Extra Trees Regressor
- MultiOutput Regressor

---

# 📈 Evaluation Metrics

Models are evaluated using:

- R² Score
- RMSE
- MAE

Performance is compared across all target currencies.

---

# 🔍 Feature Importance

The notebook analyzes which variables contribute the most to prediction.

Including:

- Gold Price
- Goldstein Scale
- Geopolitical Keywords
- Textual Features
- Engineered Features

---

# 🚀 Prediction

A reusable prediction function is implemented.

Example:

```python
event = {
    "YEAR":2023,
    "EventDescr":"Peace agreement signed",
    "GoldsteinScale_mean":3.5,
    "GOLD_PRICE_USD":1850
}

predict_exchange_rates(event)
```

---

# 📦 Technologies

| Category | Technologies |
|-----------|-------------|
| Language | Python |
| Data Processing | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| NLP | TF-IDF |
| Machine Learning | Scikit-Learn |
| Model Serialization | Joblib |

---

# 📚 Python Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn joblib
```

---

# ▶️ Running the Project

Clone the repository

```bash
git clone https://github.com/your-username/your-repository.git
```

Move to the project directory

```bash
cd your-repository
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter

```bash
jupyter notebook
```

Open

```
Notebook.ipynb
```

---

# 📈 Outputs

The notebook produces:

- Data Exploration
- Visualizations
- Model Comparison
- Performance Metrics
- Currency Predictions
- Feature Importance Analysis

---

# 🔬 Future Improvements

- Deep Learning Models
- Transformer-based NLP
- Real-time News Integration
- Live Gold Price API
- Time-Series Forecasting
- Hyperparameter Optimization
- Explainable AI (SHAP)
- Dashboard Deployment
- REST API
- Docker Support

---

# 📜 License

This project is released under the MIT License.

---

# 🙌 Acknowledgements

This project relies on the Python scientific ecosystem, including:

- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn

Special thanks to the open-source community for making advanced data science tools freely available.

---

<div align="center">

### ⭐ If you find this project useful, consider giving it a Star!

</div>
