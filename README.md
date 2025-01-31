# Zeotap-Data-Science-Assignment

eCommerce Transactions Analysis

Overview

This project involves analyzing an eCommerce Transactions dataset to derive business insights, build a Lookalike Model, and perform Customer Segmentation using clustering techniques.

Dataset Description

The dataset consists of three CSV files:

Customers.csv: Contains customer details such as CustomerID, Name, Region, and SignupDate.

Products.csv: Contains product details such as ProductID, Name, Category, and Price.

Transactions.csv: Contains transaction details including TransactionID, CustomerID, ProductID, TransactionDate, Quantity, and TotalValue.

Tasks and Deliverables

Task 1: Exploratory Data Analysis (EDA) & Business Insights

Perform EDA to identify patterns and trends.

Generate at least five business insights.

Deliverables: Jupyter Notebook/Python script & a PDF report with insights.

Task 2: Lookalike Model

Develop a model to recommend similar customers based on profile and transaction history.

Generate a Lookalike.csv file with recommendations for the first 20 customers.

Deliverables: Jupyter Notebook/Python script & Lookalike.csv file.

Task 3: Customer Segmentation (Clustering)

Perform customer segmentation using clustering techniques.

Calculate clustering metrics including DB Index.

Visualize the clusters.

Deliverables: Jupyter Notebook/Python script & a PDF report.

Installation & Setup

Prerequisites

Ensure you have the following installed:

Python 3.8+

Jupyter Notebook

Git

Required libraries: pandas, numpy, scikit-learn, seaborn, matplotlib, scipy

Install Dependencies

Run the following command to install required packages:

pip install -r requirements.txt

How to Run the Project

1. Clone the Repository

git clone https://github.com/BhanuNama/Zeotap-Data-Science-Assignment.git
cd Zeotap-Data-Science-Assignment

2. Run Jupyter Notebook

jupyter notebook

Open the respective .ipynb files for each task and execute the code.

3. Running Python Scripts (Alternative)

For standalone execution, run:

python Bhanu_Nama_EDA.ipynb
python Bhanu_Nama_Lookalike.ipynb
python Bhanu_Nama_Clustering.ipynb
