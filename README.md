🏡 California House Price Prediction

An end-to-end Machine Learning project that predicts California house prices based on socio-economic and housing features.
The project covers the complete ML lifecycle — from data preprocessing and model training to API development, user interface, and cloud deployment on Render.

🚀 Live Demo

🔗 Deployed Application: Add your Render app link here

🧠 Problem Statement

The objective of this project is to build a predictive model that estimates the median house value in California using features such as median income, house age, population, and geographical information.

📊 Dataset

Source: California Housing Dataset (scikit-learn)

Target Variable: Median House Value

Features Include:

Median Income

House Age

Average Rooms

Population

Latitude & Longitude

⚙️ Tech Stack

Programming Language: Python

Machine Learning: scikit-learn

Backend API: FastAPI

Frontend / UI: HTML/CSS / Streamlit (update if needed)

Deployment: Render

Model Serialization: Pickle (.pkl)

🔄 Project Workflow

Data loading and exploration

Data preprocessing & feature engineering

Model training and evaluation

Model serialization

API creation for inference

UI integration with backend

Cloud deployment on Render

🧪 Model & Evaluation

Model Used: Add your model name (e.g., Linear Regression / Random Forest / XGBoost)

Evaluation Metrics:

R² Score

RMSE

🔌 API Endpoint
POST /predict

Input:

{
  "MedInc": 8.3252,
  "HouseAge": 41,
  "AveRooms": 6.984,
  "Population": 322,
  "Latitude": 37.88,
  "Longitude": -122.23
}


Output:

{
  "predicted_price": 452300
}

🖥️ User Interface

The web interface allows users to input housing features and get real-time predictions by interacting with the deployed ML API.

📦 Installation & Local Setup
git clone https://github.com/your-username/california-house-price-prediction.git
cd california-house-price-prediction
pip install -r requirements.txt
uvicorn app:app --reload

📁 Project Structure
├── model/
│   └── model.pkl
├── app.py
├── requirements.txt
├── templates/
├── static/
└── README.md

🌱 Future Improvements

Add model explainability (SHAP)

Improve UI design

Add Docker support

Implement CI/CD pipeline

🙌 Acknowledgements

Scikit-learn California Housing Dataset

Render for cloud deployment

📬 Contact

Shivam Pandey
Aspiring Data Scientist | B.S. Data Science @ IIT Madras
https://www.linkedin.com/in/shivampandey9369/
