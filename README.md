# Shopping Revenue Prediction using K-Nearest Neighbors

## Overview

This project predicts whether an online shopping session will result in a purchase (Revenue = TRUE/FALSE) using the K-Nearest Neighbors (KNN) machine learning algorithm.

The project was completed as part of **HarvardX's CS50's Introduction to Artificial Intelligence with Python**.

---

## Features

- Data preprocessing from CSV
- Feature encoding for categorical values
- K-Nearest Neighbors (KNN) classification
- Model evaluation using:
  - Accuracy
  - Sensitivity (True Positive Rate)
  - Specificity (True Negative Rate)

---

## Technologies Used

- Python
- scikit-learn
- CSV
- Git & GitHub

---

## Dataset Features

The model uses the following information:

- Administrative pages visited
- Administrative duration
- Informational pages visited
- Informational duration
- Product-related pages
- Product-related duration
- Bounce Rate
- Exit Rate
- Page Values
- Special Day
- Month
- Operating System
- Browser
- Region
- Traffic Type
- Visitor Type
- Weekend

Target Variable:
- Revenue (0 = No Purchase, 1 = Purchase)

---

## Project Structure

```
shopping/
│── shopping.py
│── shopping.csv
│── requirements.txt
│── README.md
```

---

## Installation

```bash
pip install scikit-learn
```

---

## Run the Project

```bash
python shopping.py shopping.csv
```

---

## Sample Output

```
Correct: 4076
Incorrect: 856
True Positive Rate: 40.72%
True Negative Rate: 90.15%
```

---

## Learning Outcomes

Through this project I practiced:

- Data preprocessing
- Feature engineering
- Classification using KNN
- Model training and testing
- Performance evaluation using sensitivity and specificity

---

## Acknowledgements

This project was completed as part of **HarvardX's CS50's Introduction to Artificial Intelligence with Python** course on edX.
