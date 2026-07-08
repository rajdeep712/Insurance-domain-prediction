<div align="center">

# 🚗 Vehicle Insurance MLOps Pipeline

### End-to-End Production-Ready Machine Learning System with CI/CD, Docker & AWS

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python">
  <img src="https://img.shields.io/badge/FastAPI-Backend-009688?style=for-the-badge&logo=fastapi">
  <img src="https://img.shields.io/badge/MongoDB-Atlas-47A248?style=for-the-badge&logo=mongodb">
  <img src="https://img.shields.io/badge/AWS-S3%20%7C%20EC2%20%7C%20ECR-orange?style=for-the-badge&logo=amazonaws">
  <img src="https://img.shields.io/badge/Docker-Containerized-2496ED?style=for-the-badge&logo=docker">
  <img src="https://img.shields.io/badge/GitHub-Actions-2088FF?style=for-the-badge&logo=githubactions">
</p>

**A production-grade Machine Learning Operations (MLOps) project demonstrating the complete lifecycle of a machine learning model—from data ingestion to automated deployment on AWS using modern DevOps practices.**

---

</div>

# 🌟 Project Highlights

✅ End-to-End ML Pipeline

✅ Production Ready Architecture

✅ Modular & Scalable Codebase

✅ Automated Model Training

✅ Model Versioning on AWS S3

✅ Continuous Integration & Continuous Deployment

✅ Dockerized Application

✅ Cloud Deployment on AWS EC2

✅ GitHub Actions Workflow

✅ MongoDB Atlas Integration

---

# 🏗️ Complete MLOps Architecture

```text
                 Dataset
                    │
                    ▼
           MongoDB Atlas Database
                    │
                    ▼
           Data Ingestion Pipeline
                    │
                    ▼
           Data Validation Pipeline
                    │
                    ▼
        Feature Engineering Pipeline
                    │
                    ▼
          Data Transformation
                    │
                    ▼
             Model Training
                    │
                    ▼
            Model Evaluation
                    │
     Better than Previous Model?
          │                 │
         Yes                No
          │
          ▼
      Model Registry (AWS S3)
          │
          ▼
     Prediction Pipeline
          │
          ▼
      Flask/FastAPI App
          │
          ▼
        Docker Image
          │
          ▼
     Amazon ECR Registry
          │
          ▼
     GitHub Actions CI/CD
          │
          ▼
      AWS EC2 Deployment
```

---

# 🚀 Features

## 📂 Data Management

- Dataset stored in MongoDB Atlas
- Automatic MongoDB connection
- Data extraction into Pandas DataFrame
- Artifact generation
- Config-driven pipeline

---

## 🔍 Data Validation

- Schema validation
- Missing value detection
- Column validation
- Data type validation
- Training/Test file validation
- Validation reports generation

---

## ⚙️ Feature Engineering

- Data Cleaning
- Missing Value Handling
- Feature Selection
- Encoding
- Scaling
- Pipeline Serialization

---

## 🤖 Model Training

- Automated training pipeline
- Modular estimator classes
- Training artifacts
- Model serialization
- Hyperparameter ready architecture

---

## 📊 Model Evaluation

- Compare new model with production model
- Threshold-based acceptance
- Automatic model replacement
- Model performance tracking

---

## ☁️ Model Registry

- AWS S3 Integration
- Automatic model upload
- Automatic model download
- Version management
- Production model storage

---

## 🌐 Prediction Pipeline

- Batch Prediction
- Real-time Prediction
- REST API
- User Interface
- Production inference pipeline

---

## 🐳 Deployment

- Docker Containerization
- GitHub Actions CI/CD
- Amazon ECR
- Amazon EC2
- Self Hosted Runner
- Automatic Deployment

---

# 🧰 Tech Stack

## Programming

- Python 3.10

---

## Machine Learning

- Scikit-Learn
- Pandas
- NumPy

---

## Database

- MongoDB Atlas

---

## Cloud

- AWS S3
- AWS EC2
- AWS IAM
- AWS ECR

---

## DevOps

- Docker
- GitHub Actions
- CI/CD Pipeline

---

## Backend

- Flask / FastAPI

---

## Environment

- Conda
- Virtual Environment
- Environment Variables

---

## Utilities

- Logging
- Custom Exception Handling
- YAML Configuration
- Modular Package Structure

---

# 📁 Project Structure

```text
├── artifacts/
├── notebook/
├── src/
│   ├── components/
│   ├── configuration/
│   ├── constants/
│   ├── data_access/
│   ├── entity/
│   ├── aws_storage/
│   ├── pipeline/
│   ├── utils/
│   ├── logger/
│   └── exception/
│
├── static/
├── templates/
├── app.py
├── demo.py
├── requirements.txt
├── setup.py
├── pyproject.toml
├── Dockerfile
├── .dockerignore
└── .github/
    └── workflows/
```

---

# ⚡ Machine Learning Pipeline

```text
MongoDB Atlas
      │
      ▼
Data Ingestion
      │
      ▼
Data Validation
      │
      ▼
Feature Engineering
      │
      ▼
Data Transformation
      │
      ▼
Model Trainer
      │
      ▼
Model Evaluation
      │
      ▼
Model Pusher (AWS S3)
      │
      ▼
Prediction Pipeline
```

---

# 🔄 CI/CD Workflow

```text
Developer
     │
     ▼
GitHub Push
     │
     ▼
GitHub Actions
     │
     ▼
Build Docker Image
     │
     ▼
Push Image to Amazon ECR
     │
     ▼
EC2 Pulls Latest Image
     │
     ▼
Docker Container Starts
     │
     ▼
Production Application
```

---

# ☁️ AWS Services Used

| Service | Purpose                  |
| ------- | ------------------------ |
| IAM     | Secure Access Management |
| S3      | Model Registry           |
| EC2     | Application Hosting      |
| ECR     | Docker Image Registry    |

---

# 🔥 Production Features

- Production Ready Project Structure
- Modular Components
- Configuration Driven Development
- Environment Variable Management
- Logging System
- Exception Handling
- Reusable ML Pipelines
- Automatic Model Versioning
- Cloud Model Registry
- Docker Deployment
- CI/CD Automation
- GitHub Self Hosted Runner
- AWS Cloud Deployment

---

# 🛠️ Installation

```bash
git clone https://github.com/yourusername/vehicle-mlops.git

cd vehicle-mlops

conda create -n vehicle python=3.10

conda activate vehicle

pip install -r requirements.txt
```

---

# ▶️ Run Training

```bash
python demo.py
```

---

# ▶️ Run Application

```bash
python app.py
```

or

```bash
http://localhost:5000
```

---

# 🐳 Docker

Build Image

```bash
docker build -t vehicle-mlops .
```

Run Container

```bash
docker run -p 5000:5000 vehicle-mlops
```

---

# 📈 MLOps Lifecycle Covered

- Project Setup
- Data Collection
- Data Storage
- Data Ingestion
- Data Validation
- Feature Engineering
- Data Transformation
- Model Training
- Model Evaluation
- Model Registry
- Model Deployment
- Prediction Pipeline
- Dockerization
- CI/CD Automation
- Cloud Deployment
- Monitoring Ready Architecture

---

# 🎯 Skills Demonstrated

### Machine Learning

- Data Engineering
- Feature Engineering
- Model Training
- Model Evaluation
- Model Serialization

### Software Engineering

- Clean Architecture
- Modular Design
- Configuration Management
- Exception Handling
- Logging

### DevOps

- Docker
- GitHub Actions
- CI/CD
- Self Hosted Runner

### Cloud

- AWS EC2
- AWS IAM
- AWS S3
- AWS ECR

### Database

- MongoDB Atlas

---

# ⭐ Why This Project?

This project demonstrates the complete journey of taking a machine learning model from experimentation to a fully automated production deployment. It combines **Machine Learning**, **Software Engineering**, **Cloud Computing**, and **DevOps** into a scalable MLOps system following industry best practices.

---

<div align="center">

### ⭐ If you found this project useful, consider giving it a Star!

**Built with ❤️ using Python, Docker, MongoDB, AWS & GitHub Actions**

</div>
