
# BigMart Sales Analysis Prediction

🚀 End-to-end machine learning pipeline for BigMart sales prediction using Flask API, Streamlit UI, Docker, and modular Python architecture — includes EDA, model training, real-time prediction, and testing.

---

## 🗂️ Project Structure
 
```
Directory structure:
└── baladurgag24-bigmart-sales-analysis-prediction/
    ├── README.md
    ├── config.yaml
    ├── docker-compose.yml
    ├── Dockerfile
    ├── Dockerfile.streamlit
    ├── LICENSE
    ├── requirements.txt
    ├── run.txt
    ├── app/
    │   ├── __init__.py
    │   ├── api.py
    │   ├── cli.py
    │   ├── logger.py
    │   ├── model.py
    │   ├── preprocessing.py
    │   ├── streamlit_app.py
    │   ├── utils.py
    │   └── visualization.py
    ├── data/
    │   ├── test.csv
    │   └── train.csv
    ├── models/
    │   ├── feature_columns.pkl
    │   ├── label_encoders.pkl
    │   ├── model_v1.pkl
    │   └── model_v1_metrics.json
    ├── notebooks/
    │   ├── BigMart_EDA.ipynb
    │   └── Model_Training.ipynb
    └── tests/
        ├── test_preprocessing.py
        └── test_utils.py
```

---

## 📦 Features

- 🔍 **EDA**: Visualizations for data distribution and relationships
- 🧠 **Model Training**: Scikit-learn regression pipeline with preprocessing
- 🔁 **API**: Flask REST API to serve predictions
- 🌐 **Streamlit UI**: User-friendly interface for analysis and prediction
- 🐳 **Dockerized**: Fully containerized with Docker Compose
- 🧪 **Testing**: Unit tests for critical modules
- 🔧 **Modular Code**: Separated concerns across reusable components

---

## 🚀 Quick Start

1. **Clone the repo**  
```bash
git clone https://github.com/BALADURGAG24/BigMart-Sales-Analysis-Prediction.git
cd BigMart-Sales-Analysis-Prediction
```

2. **Build and run with Docker Compose**  
```bash
docker compose up --build
```

3. **Access the app**  
- API: [http://localhost:5000](http://localhost:5000)
- Streamlit UI: [http://localhost:8501](http://localhost:8501)

---

## 🛠 Tech Stack

- Python 3.10
- Pandas, Scikit-learn, Seaborn, Matplotlib
- Flask, Streamlit
- Docker, Docker Compose
- YAML, Logging
- pytest

---

## 🤝 Contributing

Feel free to fork this project and submit PRs! Feedback is welcome.

---
