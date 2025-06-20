# heart-disease-prediction
esearch project on heart disease prediction using deep learning
# Description
An interactive web application to predict and explain credit card fraud using an XGBoost model and SHAP values.
# Run Instructions
1. Clone repo and download creditcard.csv into data/ folder.
2. Train model: python backend/model/train_model.py
3. Start services: docker-compose up --build
# Tech Stack
Streamlit (frontend)
FastAPI (backend)
PostgreSQL (database)
SHAP + XGBoost (AI model)
Docker (deployment)
# API Endpoint
POST /predict — Accepts transaction features, returns prediction and SHAP explanation.
