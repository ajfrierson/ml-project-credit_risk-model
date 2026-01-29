# ml-project-credit_risk-model
# Application URL: https://ml-creditrisk-model.streamlit.app/

Credit Risk Project

Streamlit Application – Local Setup & Deployment Guide
This README explains how to run this Streamlit application on your local machine and how to deploy it for public or private access.

📦 Prerequisites
Make sure the following are installed on your system:

Python 3.8 – 3.11
Check version:
python --version
project-root/ │ ├── app.py # Main Streamlit app ├── requirements.txt # Python dependencies ├── README.md # Documentation ├── artifacts/ # Models, scalers, data files ├── utils/ # Helper modules └── .streamlit/ # (Optional) Streamlit config git clone https://github.com/your-username/your-repo.git cd your-repo


Install Dependencies:
pip install -r requirements.txt

Run Streamlit APP
streamlit run app.py
