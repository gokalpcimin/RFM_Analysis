Customer Segmentation with RFM Analysis

This repository contains a Python implementation of Customer Segmentation using the RFM (Recency, Frequency, Monetary) analysis method. The goal is to segment customers based on their purchase behavior to develop targeted marketing strategies.

Dataset
The analysis is based on the "Online Retail II" dataset, which includes sales transactions from an online retail store in the UK between 01/12/2009 - 09/12/2011. The dataset can be found at the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Online+Retail+II).

Project Structure
1. Business Problem**: Defines the objective of the analysis.
2. Data Understanding**: Explores the dataset and its attributes.
3. Data Preparation**: Prepares the data by handling missing values, removing canceled transactions, and creating new variables.
4. Calculating RFM Metrics**: Calculates the Recency, Frequency, and Monetary metrics for each customer.
5. Calculating RFM Scores**: Assigns scores to each RFM metric.
6. Creating & Analyzing RFM Segments**: Segments customers based on their RFM scores and analyzes these segments.
7. Function for the Entire Process**: Wraps the entire process into a reusable function.

Files
- `rfm_analysis.py`: Contains the full implementation of the RFM analysis.
- `new_customers.csv`: List of new customers identified in the analysis.
- `rfm.csv`: Detailed RFM scores and segments for all customers.

How to Use
1. Clone the repository.
2. Install the required packages: `pandas`, `numpy`.
3. Download the dataset and place it in the `datasets` folder.
4. Run `rfm_analysis.py` to perform the RFM analysis and generate the results.
