# ✈️ Flight Price Prediction Using Machine Learning

An end-to-end **Machine Learning** project that predicts domestic Indian flight ticket prices using historical flight data. The project compares multiple regression algorithms, evaluates their performance, and deploys the best-performing model through an interactive **Streamlit** web application.

---

## 📖 Overview

Airline ticket prices change dynamically based on factors such as:

- 📅 Booking date
- ✈️ Airline
- 🛫 Source & Destination
- ⏰ Departure & Arrival Time
- 🕒 Duration
- 📈 Demand and seasonality

This project builds a machine learning pipeline capable of predicting flight prices from these features. Several regression models were trained and compared, with **Random Forest Regressor** achieving the best overall performance.

---

## ✨ Features

- Data preprocessing and cleaning
- Feature engineering
- Exploratory Data Analysis (EDA)
- Multiple regression model comparison
- Hyperparameter tuning
- Performance evaluation using standard regression metrics
- Interactive Streamlit dashboard
- Prediction uncertainty estimation
- Route insights and booking recommendations

---

## 🛠️ Tech Stack

### Programming Language

- Python

### Libraries

- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Matplotlib
- Seaborn
- Joblib
- Streamlit

---

## 📂 Dataset

**Dataset:** Flight Price Prediction Dataset

- **Source:** Kaggle
- **Records:** 300,153 domestic Indian flight records

The dataset contains features such as:

- Airline
- Source
- Destination
- Journey Date
- Departure Time
- Arrival Time
- Duration
- Stops
- Flight Class
- Price

---

## 🤖 Machine Learning Models

The following regression models were trained and evaluated:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- XGBoost Regressor

---

## 📊 Model Performance

| Model | Performance |
|--------|-------------|
| Linear Regression | Baseline model |
| Decision Tree | Better nonlinear learning |
| XGBoost | High accuracy |
| **Random Forest** | ⭐ Best Overall Model |

### Best Model Results

| Metric | Score |
|---------|------:|
| RMSE | **2373.68** |
| MAE | **857.08** |
| R² Score | **0.9891** |

---

## 🚀 Streamlit Dashboard

The deployed application allows users to:

- Predict flight prices
- Enter custom flight details
- View prediction uncertainty
- Compare with similar historical flights
- Explore route insights
- Analyze booking windows

---

## 📁 Project Structure

```
Flight-Price-Prediction/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── models/
│   ├── random_forest.pkl
│   ├── xgboost.pkl
│   └── preprocessing.pkl
│
├── notebooks/
│
├── app/
│   └── streamlit_app.py
│
├── images/
│
├── requirements.txt
├── Project_Report.tex
└── README.md
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/Flight-Price-Prediction.git

cd Flight-Price-Prediction
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the Streamlit application:

```bash
streamlit run app/streamlit_app.py
```

---

## 📈 Workflow

```
Dataset
    │
    ▼
Data Cleaning
    │
    ▼
Feature Engineering
    │
    ▼
Model Training
    │
    ▼
Model Evaluation
    │
    ▼
Best Model Selection
    │
    ▼
Streamlit Deployment
```

---

## 🎯 Objectives

- Predict domestic flight prices accurately.
- Compare multiple machine learning regression algorithms.
- Build an interactive prediction system.
- Help users make informed booking decisions.

---

## 📚 Evaluation Metrics

The models were evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## 🔮 Future Improvements

- Live airline API integration
- Real-time price tracking
- Deep Learning models
- Automated retraining pipeline
- Cloud deployment
- Personalized booking recommendations

---

## 👨‍💻 Authors

- Mohammed Jasim
- Ibrahim Ansari
- Chayan Raj Bharati
- Omkar Darekar

**Guide**

Dr. Jayshree Ghorpade-Aher

School of Computer Engineering and Technology  
MIT World Peace University (MIT-WPU), Pune

---

## 📄 License

This project is developed for academic and educational purposes at **MIT World Peace University (MIT-WPU)**.

---

## ⭐ Acknowledgements

- MIT World Peace University
- Kaggle Flight Price Prediction Dataset
- Scikit-learn
- XGBoost
- Streamlit
