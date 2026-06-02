Support Ticket Classification System

Project Overview

This project focuses on automatically classifying customer support tickets into different categories and predicting their priority levels using Machine Learning and Natural Language Processing (NLP) techniques.

The system helps support teams identify ticket types quickly and prioritize customer issues efficiently, resulting in faster response times and improved customer satisfaction.

---

Objective

To build a machine learning model that:

- Classifies customer support tickets into predefined categories.
- Predicts ticket priority levels.
- Performs text preprocessing and feature extraction.
- Evaluates model performance using classification metrics.

---

Dataset

Dataset Name: customer_support_tickets_200k.csv

Columns Used

- issue_description
- category
- priority

---

Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- TF-IDF Vectorization
- Matplotlib
- Jupyter Notebook

---

Project Workflow

1. Data Collection

Loaded the customer support ticket dataset.

2. Data Preprocessing

- Removed unnecessary characters
- Converted text to lowercase
- Cleaned ticket descriptions

3. Feature Extraction

Used TF-IDF Vectorization to convert text into numerical features.

4. Ticket Category Classification

Trained a Machine Learning model to classify tickets into categories.

5. Priority Prediction

Built a model to predict ticket priority levels.

6. Model Evaluation

Evaluated performance using:

- Accuracy Score
- Classification Report
- Confusion Matrix

7. Visualization

Generated:

- Category Distribution Graph
- Priority Distribution Graph

---

Key Features

✔ Text Cleaning & Preprocessing

✔ Ticket Category Classification

✔ Priority Prediction

✔ Model Performance Evaluation

✔ Data Visualization

---

Results

The machine learning model successfully classifies customer support tickets and predicts their priority levels based on ticket descriptions.

---

Project Structure

FUTURE_ML_02

├── customer_support_tickets_200k.zip

├── Support_Ticket_Classification.ipynb

├── outputs.pdf

├── category_distribution.png

├── priority_distribution.png

└── README.md

---

Future Improvements

- Implement advanced NLP techniques.
- Deploy the model as a web application.
- Improve classification accuracy using ensemble models.
- Enable real-time ticket prediction.

---

Author

K.Divya

Machine Learning Intern

Future Interns
