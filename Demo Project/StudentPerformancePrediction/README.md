# Student Performance Prediction ML

A machine learning project using classifiers to analyze and predict key factors that affect student grades based on data stored in a CSV file.

## Overview

This project processes a dataset containing student records across various nationalities and grade levels. It evaluates determining factors such as the number of hands raised in class, attendance rate, and study hours. Multiple machine learning models and classifiers are trained to identify which factors most accurately predict academic outcomes. Visualizations—including heatmaps, graphs, and confusion matrices—are included to demonstrate data engineering and model evaluation results.

---

## Setup and Installation

### Prerequisites

* Python 3.8 or higher
* `pip` package manager

### 1. Clone the Repository

```bash
git clone [https://github.com/heysanzu/RAYBYTE.git](https://github.com/heysanzu/RAYBYTE.git)
cd RAYBYTE/"Demo Project"/StudentPerformancePrediction

```

### 2. Create a Virtual Environment

* **macOS / Linux:**
```bash
python3 -m venv venv
source venv/bin/activate

```


* **Windows:**
```cmd
python -m venv venv
venv\Scripts\activate

```



### 3. Install Dependencies

```bash
pip install pandas numpy scikit-learn matplotlib seaborn

```

---

## Project Structure

* **data/**: Contains the dataset CSV file (e.g., student attendance, engagement metrics, and grades).
* **main.py / notebook.ipynb**: Script containing data preprocessing, EDA visualizations, model training, and performance evaluations.
* **README.md**: Documentation and project setup instructions.

---

## Usage

1. Ensure your dataset CSV file is placed inside the project directory.
2. Execute the main Python script:
```bash
python main.py

```
