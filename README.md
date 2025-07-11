# Visa Approval Prediction

This project builds a machine learning model to predict the approval or rejection of US visa applications using a full MLOps pipeline. It integrates data handling, model development, and cloud deployment using scalable tools and services.

---

## 🔧 Tech Stack

- **Python & Jupyter Notebook** – For data preprocessing, feature engineering, and model experimentation.
- **Visual Studio Code** – For modular, maintainable code development with Git integration.
- **MongoDB** – Stores visa application data in a scalable NoSQL format.
- **FastAPI** – Serves predictions via a high-performance REST API.
- **GitHub** – Handles version control and team collaboration.
- **GitHub Actions & Self-hosted Runner** – Automates training, testing, and deployment workflows.
- **AWS S3** – Cloud storage for datasets and model artifacts.
- **AWS ECR & EC2** – Dockerized model deployment on cloud compute.
- **AWS IAM** – Secure access management for AWS resources.

---

## 📁 Project Structure

1. constant
2. config_entity
3. artifact_entity
4. conponent
5. pipeline
6. app.py / demo.py

---

## 🌐 Environment Variables

Before running the project, export the following:

```bash
export MONGODB_URL="mongodb+srv://<username>:<password>@cluster.mongodb.net/<db>"
export AWS_ACCESS_KEY_ID=<your_aws_access_key>
export AWS_SECRET_ACCESS_KEY=<your_aws_secret_key>
```

## 🔁 Workflow Summary
Data ingestion and preprocessing

Model training and evaluation

Model packaging using Docker

CI/CD with GitHub Actions

Deployment to AWS EC2 via container pulled from AWS ECR

## Setup github secrets:
AWS_ACCESS_KEY_ID
AWS_SECRET_ACCESS_KEY
AWS_DEFAULT_REGION
ECR_REPO
