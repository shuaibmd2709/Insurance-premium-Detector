# Insurance-premium-Detector

A production-ready machine learning application that predicts insurance premiums based on user input. The system is built using a FastAPI backend for model inference and a Streamlit frontend for interactive user experience, fully containerized with Docker and deployed on AWS.

🚀 Project Overview

This project demonstrates an end-to-end ML deployment pipeline:

A trained machine learning model predicts insurance premiums

A FastAPI backend exposes the model via REST API

A Streamlit frontend provides an intuitive user interface

Docker ensures consistent and reproducible environments

Deployment is handled via Docker Hub and AWS Cloud

🧰 Tech Stack

- Backend

  - FastAPI

  - Uvicorn

  - Scikit-learn / ML model (Pickle)

- Frontend

  - Streamlit

  - Requests (API communication)

- DevOps / Deployment

  - Docker
  - AWS Cloud(EC2)

⚙️ How It Works

- User enters details (e.g., age, BMI, smoking status) via Streamlit UI

- Frontend sends a POST request to FastAPI backend

- Backend loads the trained model (model.pkl)

- Model predicts insurance premium

- Prediction is returned and displayed in UI

🌐 Access the Application

Frontend (Streamlit UI):
http://localhost:8501

Backend API Docs (FastAPI Swagger):
http://localhost:8000/docs

☁️ Deployment

This project is fully containerized and deployed using:

- Docker Hub → Image hosting

- AWS Cloud → Application deployment
