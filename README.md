# 🚗 Car Dataset Analysis

This repository contains a Jupyter Notebook that performs data cleaning, exploration, and filtering operations on a car dataset. The project demonstrates how to process real-world tabular data using Python and pandas.

---

## 📓 Notebook Overview

**`Car Notebook.ipynb`** includes:
- Loading a CSV file of car specifications
- Identifying and handling missing values
- Value count analysis for categorical columns
- Filtering data based on specific conditions
- Creating new derived columns

---

## 🧾 Dataset Description

The dataset contains specifications of various cars including:
- **Make** (car brand)
- **Cylinders**
- **Weight**
- **MPG_City**
- **Origin** (e.g., Asia, Europe)

> **Note:** The dataset file used is `Project+2+-+Cars+Dataset.csv`  
> Make sure it is located in the `../Datasets/` directory or update the path in the notebook.

---

## 🧹 Data Cleaning Steps

- Checked for and handled null values
- Replaced missing values in the `Cylinders` column with the mean
- Dropped completely empty rows

---

## 📊 Analysis Performed

1. **Value Counts**  
   Counted the occurrences of each car make using `.value_counts()`.

2. **Filtering**  
   Displayed only cars originating from **Asia** or **Europe**.

3. **Conditional Removal**  
   Removed all cars with a weight over 4000.

4. **Column Transformation**  
   Created a new column `MPG_City_` with values = `MPG_City + 3`.

---

## 🛠️ Requirements

Install necessary dependencies:

```bash
pip install pandas
```
## Running the Notebook
1. Clone the repository:

```bash
git clone https://github.com/your-username/car-dataset-analysis.git
cd car-dataset-analysis
```
2. Launch Jupyter Notebook:

```bash
jupyter notebook
```
3. Open Car Notebook.ipynb and run the cells to explore and analyze the dataset.

