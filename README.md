# Student Performance Prediction – End-to-End Machine Learning Project

An end-to-end Machine Learning project that demonstrates the complete ML development lifecycle, from data preprocessing and model training to prediction and deployment using Flask.

## Overview

This project focuses on building a machine learning pipeline for student performance prediction. It demonstrates how machine learning techniques can be applied to structured data to develop a predictive system.

The project covers the major stages of an end-to-end ML workflow, including data ingestion, data transformation, model training, evaluation, and deployment.

## Key Features

- **Data Ingestion:** Loading and organizing the dataset for model development.
- **Data Preprocessing:** Handling missing values, encoding categorical variables, and preparing features.
- **Model Training:** Training and evaluating machine learning models.
- **Model Serialization:** Saving trained models and preprocessing objects using Pickle.
- **Prediction Pipeline:** Implementing a reusable pipeline for making predictions on new data.
- **Web Application:** Integrating the trained model with a Flask application.

## Tech Stack

| Category | Technologies |
|---|---|
| Programming Language | Python |
| Data Processing | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn |
| Deployment | Flask |
| Model Serialization | Pickle |
| Development Environment | Jupyter Notebook, VS Code |

## Project Structure

```text
Student-Performance-Prediction/
│
├── artifacts/
│   ├── model.pkl
│   ├── preprocessor.pkl
│   ├── train.csv
│   └── test.csv
│
├── notebook/
│   └── stud.csv
│
├── src/
│   ├── components/
│   │   ├── data_ingestion.py
│   │   ├── data_transformation.py
│   │   └── model_trainer.py
│   │
│   ├── pipeline/
│   │   ├── train_pipeline.py
│   │   └── predict_pipeline.py
│   │
│   ├── exception.py
│   ├── logger.py
│   └── utils.py
│
├── templates/
│   ├── home.html
│   └── index.html
│
├── app.py
├── requirements.txt
├── setup.py
└── README.md
```

## Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/itskusal7/Student-Performance-Prediction.git
cd Student-Performance-Prediction
```

### 2. Create a Virtual Environment

```bash
python -m venv .venv
```

Activate it:

**macOS / Linux**

```bash
source .venv/bin/activate
```

**Windows**

```bash
.venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Application

```bash
python app.py
```

Open the local URL displayed in your terminal in a web browser.

## Machine Learning Workflow

1. Data Collection and Ingestion
2. Exploratory Data Analysis
3. Data Cleaning and Preprocessing
4. Feature Transformation
5. Model Training
6. Model Evaluation
7. Model Serialization
8. Prediction Pipeline
9. Flask Application Deployment

## Results and Evaluation

| Evaluation Metric | Result |
|---|---|
| Model Used | Ridge Regression |
| R² Score | 0.8806 (88.06%) |

## Learning Outcomes

- Developed an understanding of end-to-end machine learning project development.
- Gained practical experience in modular Python programming.
- Implemented reusable data ingestion and transformation components.
- Learned model serialization and prediction pipeline development.
- Integrated a trained machine learning model into a Flask web application.

## Learning Resources and Acknowledgements

This project was developed as an independent learning and implementation exercise, with guidance and reference from **Krish Naik's End-to-End Machine Learning Project tutorial**.

The tutorial helped me understand the architecture and workflow of production-oriented machine learning projects. I implemented and adapted the concepts while developing my own project.

## Author

**Kushal Sapkota**

- GitHub: https://github.com/itskusal7
- LinkedIn: https://www.linkedin.com/in/kushal-sapkota-a039301b3/

---

*If you find this project useful, feel free to explore the repository and share feedback.*
