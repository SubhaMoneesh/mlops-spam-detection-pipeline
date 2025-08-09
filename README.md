# Automated Spam Detection using a Production-Ready MLOps Pipeline

## Description:
This project focuses on building a robust MLOps pipeline for a text classification task. It demonstrates how to move a machine learning model from a development environment to a production-ready, automated system. The pipeline handles data ingestion, model training, and deployment as a RESTful API, with a mechanism for monitoring and retraining to ensure performance over time.

---

## Features:

**Data Pipeline:** Automated script to ingest and preprocess raw email text data.

**Model Training:** Trains a text classification model (e.g., using a deep learning architecture) to detect spam with high accuracy.

**RESTful API:** Deploys the trained model as a Flask-based microservice for real-time predictions.

**Containerization:** The entire pipeline, including the API, is containerized using Docker for portability and scalability.

**Performance Monitoring:** A system to monitor the model's accuracy and latency in production.

**Automated Retraining:** The pipeline can be triggered to automatically retrain the model with new data to prevent performance degradation.

---

## Tech Stack:

**Programming Language:** Python

**Machine Learning:** TensorFlow/PyTorch, Scikit-learn

**Backend:** Flask

**Containerization:** Docker

**Version Control:** Git

**Orchestration (planned):** Apache Airflow or Prefect

---

## Installation:

**Clone the repository:**
```bash
git clone [repository_url]
```
**Navigate to the project directory:**
```bash
cd [project_name]
```
**Build the Docker image:**
```bash
docker build -t spam-detector .
```
**Run the container:**
```bash
docker run -p 5000:5000 spam-detector
```
**Access the API at** 
```arduino
http://localhost:5000
```
