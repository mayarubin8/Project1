# Project 1 – Data Acquisition, Cleaning, Preprocessing and Feature Engineering for Exploratory Analysis

This repository contains the full workflow for Project 1.

The project demonstrates a complete data science pipeline including:

- Data acquisition
- Data cleaning
- Exploratory Data Analysis (EDA)
- Data preprocessing
- Feature engineering
- Final processed dataset generation

---

# Quick Start

```bash
git clone https://github.com/mayarubin8/Project1.git
cd PROJECT1

python3 -m venv .venv
source .venv/bin/activate      # Mac/Linux
# .venv\Scripts\activate       # Windows

pip install -r requirements.txt
```

Open:

```
notebook/Project_1_step1&2&3&4.ipynb
```

Select the `.venv` kernel and click **Run All**.

---

# Project Structure

```
PROJECT1/
│
├── data/
│   ├── raw/
│   │   └── listings.csv
│   │
│   └── cleaned/
│       └── airbnb_final_processed_dataset.csv
│
├── notebook/
│   └── Project_1_step1&2&3&4.ipynb
│
├── requirements.txt
└── README.md
```

---

# Setup Instructions

## Clone Repository

```bash
git clone https://github.com/mayarubin8/Project1.git
cd PROJECT1
```

## Create Virtual Environment

### Mac / Linux

```bash
python3 -m venv .venv
source .venv/bin/activate
```

### Windows

```bash
python -m venv .venv
.venv\Scripts\activate
```

## Install Dependencies

```bash
pip install -r requirements.txt
```

Required libraries include:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- scipy
- ...

---

# Running the Notebook

Open the notebook:

```
notebook/Project_1_step1&2&3&4.ipynb
```

Make sure the `.venv` environment is selected.

Then click:

```
Run All
```

The notebook will execute the full pipeline:

- Data Cleaning
- EDA
- Preprocessing
- Feature Engineering
- Final Dataset Export

---

# Datasets

## Raw Dataset

```
data/raw/listings.csv
```

Original dataset used for data acquisition and cleaning.

---

## Final Processed Dataset

```
data/cleaned/airbnb_final_processed_dataset.csv
```

Generated at the end of the notebook.

This dataset includes:

- Encoded categorical variables
- Scaled numerical features
- Engineered features
- Outlier-handled distributions

It is modeling-ready.


---

# Team Contributions

- Maya – Data Cleaning
- Yuxuan – EDA
- Jiahao & Jiarong – Preprocessing & Feature Engineering

---

# Requirements

Python 3.10+ recommended.
