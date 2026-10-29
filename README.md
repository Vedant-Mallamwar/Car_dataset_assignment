# 🚗 Car Dataset Analysis

## 📌 Project Overview

This project focuses on analyzing a car dataset using Python and Pandas. The assignment explores car prices, mileage, fuel types, transmission types, manufacturing years, engine sizes, and brands to understand the dataset and identify useful insights.

## 🎯 Objectives

- Analyze car prices and vehicle attributes.
- Find cars with mileage greater than 200,000.
- Analyze the distribution of cars by transmission type.
- Identify the car model with the highest price.
- Calculate the average price by fuel type.
- Find cars manufactured in 2020 or later.
- Calculate the average engine size for each brand.
- Identify the car with the lowest mileage.
- Calculate the correlation between mileage and price.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab

## 📂 Project Structure

```text
Car_dataset_assignment/
│
├── car_price_dataset.csv
├── Car_Dataset_Analysis.ipynb
└── README.md
```

*Note: Update the filenames above to match the actual files in your repository.*

## ⚙️ Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/Vedant-Mallamwar/Car_dataset_assignment.git
```

### 2. Open the project folder

```bash
cd Car_dataset_assignment
```

### 3. Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn
```

### 4. Run the notebook

Open the Jupyter Notebook file or upload it to Google Colab to execute the analysis.

## 📊 Data Analysis Questions

The assignment covers the following questions:

1. What is the average price of cars?
2. How many cars have a mileage greater than 200,000?
3. What is the distribution of cars by transmission type?
4. Which car model has the highest price?
5. What is the average price of cars by fuel type?
6. How many cars were manufactured in 2020 or later?
7. What is the average engine size for each brand?
8. Which car has the lowest mileage?
9. What is the correlation between mileage and price?

## 💻 Sample Python Code

```python
import pandas as pd

# Load the dataset
df = pd.read_csv("car_price_dataset.csv")

# Display the first five rows
print(df.head())

# Check dataset information
print(df.info())

# Calculate average car price
print(df["Price"].mean())

# Calculate correlation between mileage and price
print(df["Mileage"].corr(df["Price"]))
```

*Note: Adjust the file path and column names according to your dataset.*

## 📈 Key Learning Outcomes

- Data loading and inspection using Pandas.
- Filtering and selecting data.
- Calculating averages and correlations.
- Grouping and analyzing data by categories.
- Identifying maximum and minimum values.
- Solving practical data analysis problems using Python.

## 👨‍💻 Author

**Vedant Mallamwar**

- GitHub Profile: [Vedant-Mallamwar](https://github.com/Vedant-Mallamwar)
- Project Repository: [Car_dataset_assignment](https://github.com/Vedant-Mallamwar/Car_dataset_assignment)

## 📄 License

This project is created for educational purposes as part of a data analysis assignment.
