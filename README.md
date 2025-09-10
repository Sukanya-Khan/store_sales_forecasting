🚀 Features

✅ High accuracy: Prophet (95.3%), XGBoost (94.1%), LSTM (93.7%)

🧠 Deep learning with LSTM loss visualization
📈 Prophet trend & seasonality decomposition
📉 XGBoost vs LSTM vs Prophet forecast comparison
💻 Flask-based dashboard with Bootstrap + Neon CSS
🌈 Modern glassmorphism UI + hover animations
🔁 MLOps-ready modular pipeline & logging structure
📂 Clean, extensible project architecture

📁 Project Structure
store_sales_forecasting/
├── app.py               # Flask dashboard app
├── templates/
│   └── index.html       # Dashboard frontend (Bootstrap + Glassmorphism)
├── models/              # Saved models & generated plots
├── data/                # Raw Kaggle dataset
├── logs/                # Future: logs & MLflow integration
├── notebooks/           # Jupyter notebooks (exploration/EDA)
├── src/
│   ├── preprocessing.py # Data cleaning & feature engineering
│   ├── train_prophet.py # Train Prophet model
│   ├── train_xgboost.py # Train XGBoost model
│   └── train_lstm.py    # Train LSTM model with Keras/TensorFlow
└── requirements.txt

⚙️ Installation

Requirements:

Python 3.9+

pandas, numpy, scikit-learn

xgboost

matplotlib, seaborn

tensorflow / keras

prophet

flask, jinja2

Install dependencies:

pip install -r requirements.txt

🔧 How to Run

Clone the repository

git clone https://github.com/username/store-sales-forecasting.git
cd store-sales-forecasting


Download dataset

Source: Kaggle Store Sales Time Series Forecasting

Place CSV files inside data/ folder

Preprocess & Train Models

python src/preprocessing.py
python src/train_prophet.py
python src/train_xgboost.py
python src/train_lstm.py


Launch Dashboard

python app.py


Go to 👉 http://localhost:5000

🧠 Model Performance
Model	Accuracy
Prophet	95.3%
XGBoost	94.1%
LSTM	93.7%
✨ Dashboard Preview

Built with Flask + Bootstrap 5

Neon-glass inspired design

Interactive hover effects

Clean and modern UI

(Add screenshots here if available)

📌 Future Improvements

🔄 Dropdown filters (stores, categories, time range)

☁️ Deployment on Render / HuggingFace Spaces

📈 Interactive plots with Plotly/Dash

🧪 MLflow integration for experiment tracking

🧹 Automated retraining & scheduled updates

📚 Credits

Dataset: Kaggle Store Sales Forecasting

Frameworks & Libraries: TensorFlow/Keras, Facebook Prophet, XGBoost, Flask

UI Inspiration: Bootstrap + Glassmorphism CSS

**👨‍💻 Author

Srizoni Maity – B.Tech CSE (Data Science)
Sukanya khan - B.Tech CSE (Data Science)
Baishakhi sing - B.Tech CSE (Data Science)
Curious | Creative | Exploring MLOps & AI for real-world impact

