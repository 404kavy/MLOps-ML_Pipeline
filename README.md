# 🚀 End-to-End MLOps Machine Learning Pipeline with DVC

A production-inspired end-to-end Machine Learning pipeline built using Python and DVC (Data Version Control). This project demonstrates how to build a reproducible, modular, and version-controlled ML workflow following MLOps best practices.

---

## 📌 Project Overview

This project implements a complete machine learning pipeline from data ingestion to model evaluation while maintaining reproducibility, experiment tracking, and version control using DVC.

The pipeline is modular, configurable, and designed following software engineering principles.

---

## 🏗️ Pipeline Architecture

```
Data Ingestion
      │
      ▼
Data Validation
      │
      ▼
Data Preprocessing
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
Metrics & Reports
```

---

# ✨ Features

- Modular ML Pipeline
- Data Versioning using DVC
- Model Versioning
- Reproducible Pipelines
- Experiment Tracking with DVC
- Parameter Management using YAML
- JSON Metrics Reporting
- Centralized Logging
- Exception Handling
- Configuration Driven Design
- Git Integration
- AWS S3 Remote Storage Support

---

# 🛠️ Technologies Used

### Programming

- Python 3.x

### Machine Learning

- Scikit-Learn
- NumPy
- Pandas

### MLOps

- DVC
- DVCLive
- Git
- AWS S3 (DVC Remote)

### Configuration

- YAML

### Logging

- Python Logging

### Serialization

- Pickle

---

# 📂 Project Structure

```
.
├── data/
│   ├── raw/
│   ├── processed/
│
├── models/
│
├── reports/
│
├── logs/
│
├── src/
│   ├── data_ingestion.py
│   ├── data_preprocessing.py
│   ├── feature_engineering.py
│   ├── model_building.py
│   ├── model_evaluation.py
│
├── params.yaml
├── dvc.yaml
├── dvc.lock
├── requirements.txt
└── README.md
```

---

# 🔄 DVC Workflow

This project demonstrates:

- DVC Data Versioning
- DVC Pipeline Creation
- DVC Pipeline Reproduction
- DVC Experiment Tracking
- DVC Metrics Tracking
- Parameter Tracking
- Dependency Tracking
- Output Tracking
- Remote Storage Integration
- Git + DVC Workflow

---

# 📊 Metrics

The evaluation stage generates:

- Accuracy
- Precision
- Recall
- ROC-AUC Score

Metrics are stored inside:

```
reports/metrics.json
```

---

# ⚙️ Pipeline Execution

Run the complete pipeline

```bash
dvc repro
```

Run experiments

```bash
dvc exp run
```

View experiments

```bash
dvc exp show
```

Apply an experiment

```bash
dvc exp apply
```

Push data/models to remote

```bash
dvc push
```

Pull data/models

```bash
dvc pull
```

---

# 💡 MLOps Concepts Demonstrated

- End-to-End ML Pipeline
- Reproducible Machine Learning
- Data Versioning
- Model Versioning
- Pipeline Automation
- Experiment Management
- Configuration Management
- Software Engineering Best Practices
- Modular Project Structure
- Production-Oriented Workflow

---

# 📈 Skills Demonstrated

- Python
- Machine Learning
- Scikit-Learn
- Data Preprocessing
- Feature Engineering
- Model Training
- Model Evaluation
- DVC
- DVCLive
- Git
- AWS S3
- YAML Configuration
- Logging
- JSON Reporting
- Reproducible ML Pipelines
- MLOps Fundamentals

---

# 🚀 Future Improvements

- MLflow Integration
- Docker
- FastAPI Deployment
- CI/CD with GitHub Actions
- AWS Deployment
- Model Monitoring
- Kubernetes

---

## ⭐ If you found this project helpful, consider giving it a star!
