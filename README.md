# # eCommerce Data Science Assignment: Transactions Dataset

## Overview

This assignment involves analyzing an eCommerce transactions dataset to extract valuable business insights, build predictive models, and provide actionable recommendations. The task is divided into three key parts: Exploratory Data Analysis (EDA), Lookalike Model creation, and Customer Segmentation using clustering techniques.

The assignment requires the application of various data science concepts such as data cleaning, machine learning, business analysis, and visualization.

## Dataset Description

The following datasets are provided:

- **Customers.csv**: Contains information about customers including their unique ID, region, signup date, etc.
- **Products.csv**: Contains product details such as product ID, category, and price.
- **Transactions.csv**: Contains transaction details, including transaction ID, product purchased, transaction date, quantity, and total value.

### Files in the dataset:

1. **Customers.csv**
   - `CustomerID`: Unique identifier for each customer.
   - `CustomerName`: Name of the customer.
   - `Region`: Continent where the customer resides.
   - `SignupDate`: Date when the customer signed up.

2. **Products.csv**
   - `ProductID`: Unique identifier for each product.
   - `ProductName`: Name of the product.
   - `Category`: Product category.
   - `Price`: Product price in USD.

3. **Transactions.csv**
   - `TransactionID`: Unique identifier for each transaction.
   - `CustomerID`: ID of the customer who made the transaction.
   - `ProductID`: ID of the product sold.
   - `TransactionDate`: Date of the transaction.
   - `Quantity`: Quantity of the product purchased.
   - `TotalValue`: Total value of the transaction.
   - `Price`: Price of the product sold.

## Task Breakdown

### Task 1: Exploratory Data Analysis (EDA) and Business Insights (25%)

1. **Perform EDA** on the provided dataset, including:
   - Data Cleaning and Preparation
   - Generating Summary Statistics
   - Visualizing key data trends (e.g., transactions over time, revenue by region, popular product categories)
   
2. **Business Insights**:
   - Derive at least 5 business insights from the analysis, such as:
     - Key trends in customer behavior
     - Popular product categories
     - Regional revenue insights
     - Transaction patterns over time

### Task 2: Lookalike Model (30%)

1. **Build a Lookalike Model** that recommends similar customers based on their profile and transaction history. The model should:
   - Use both customer and product information.
   - Assign a similarity score to each recommended customer.
   
2. **Deliverables**:
   - A file named `Dhanush_B_A_Lookalike.csv` containing the top 3 lookalikes for the first 20 customers (CustomerID: C0001 - C0020), along with their similarity scores.
   - A Jupyter Notebook (`Dhanush_B_A_Lookalike.ipynb`) explaining the model development and implementation.

### Task 3: Customer Segmentation / Clustering (30%)

1. **Customer Segmentation**:
   - Use clustering techniques to segment customers based on both their profile (from Customers.csv) and transaction data (from Transactions.csv).
   - Choose an appropriate clustering algorithm (e.g., K-means, DBSCAN) and define the number of clusters (between 2 and 10).
   
2. **Metrics and Evaluation**:
   - Calculate clustering metrics like the **DB Index** to evaluate the quality of clusters.
   - Visualize clusters with relevant plots (e.g., scatter plots, cluster distributions).
   
3. **Deliverables**:
   - A PDF report containing clustering results, including the number of clusters formed and DB Index value.
   - A Jupyter Notebook (`Dhanush_B_A_Clustering.ipynb`) containing the clustering code and analysis.

## File Structure

├── Customers.csv # The customers dataset containing customer details ├── Products.csv # The products dataset containing product details ├── Transactions.csv # The transactions dataset containing transaction details ├── Dhanush_B_A_EDA.ipynb # Jupyter Notebook containing the EDA code ├── Dhanush_B_A_EDA.pdf # PDF report summarizing business insights from EDA ├── Dhanush_B_A_Lookalike.csv # CSV file with the top 3 lookalike recommendations and similarity scores ├── Dhanush_B_A_Lookalike.ipynb # Jupyter Notebook explaining the Lookalike model development ├── Dhanush_B_A_Clustering.pdf # PDF report containing clustering results and analysis (DB Index, number of clusters) ├── Dhanush_B_A_Clustering.ipynb # Jupyter Notebook containing the clustering code and analysis └── README.md # The README file describing the project, datasets, and deliverables


### Explanation:

- **Customers.csv**, **Products.csv**, and **Transactions.csv**: These datasets should be included in your folder, as provided in the assignment.
- **Dhanush_B_A_EDA.ipynb**: The Jupyter Notebook containing the code for exploratory data analysis (EDA).
- **Dhanush_B_A_EDA.pdf**: The PDF report summarizing the business insights derived from your EDA.
- **Dhanush_B_A_Lookalike.csv**: This CSV file should contain the recommendations of 3 similar customers (for CustomerID: C0001 - C0020) based on the Lookalike model, along with similarity scores.
- **Dhanush_B_A_Lookalike.ipynb**: The Jupyter Notebook explaining your Lookalike model and its implementation.
- **Dhanush_B_A_Clustering.pdf**: The PDF report summarizing the customer segmentation results, including the DB Index and the number of clusters.
- **Dhanush_B_A_Clustering.ipynb**: The Jupyter Notebook containing the clustering algorithm and analysis code.
- **README.md**: This file, which provides an overview of the project and submission instructions.

Ensure that all files follow this structure for clarity and organization.


## How to Run

1. **Download the Datasets**: The datasets can be downloaded from the provided Google Drive links:
   - [Customers.csv](https://drive.google.com/file/d/1bu_--mo79VdUG9oin4ybfFGRUSXAe-WE/view?usp=sharing)
   - [Products.csv](https://drive.google.com/file/d/1IKuDizVapw-hyktwfpoAoaGtHtTNHfd0/view?usp=sharing)
   - [Transactions.csv](https://drive.google.com/file/d/1saEqdbBB-vuk2hxoAf4TzDEsykdKlzbF/view?usp=sharing)
   
2. **Upload the Files**: Once you’ve downloaded the files, upload them to your Google Colab or local environment.

3. **Execute the Notebooks**:
   - Open the respective Jupyter Notebooks (`EDA`, `Lookalike`, `Clustering`), and run each code block sequentially to perform the tasks.
   - The final outputs will include the business insights, clustering results, and lookalike recommendations.

4. **Save Your Outputs**: Once you have completed all tasks, save the outputs and report files as per the naming convention mentioned below.

## File Naming Convention

Ensure your files follow this naming convention to avoid disqualification:
- `Dhanush_B_A_EDA.pdf`
- `Dhanush_B_A_EDA.ipynb`
- `Dhanush_B_A_Lookalike.csv`
- `Dhanush_B_A_Lookalike.ipynb`
- `Dhanush_B_A_Clustering.pdf`
- `Dhanush_B_A_Clustering.ipynb`

## Evaluation Criteria

Your submission will be evaluated based on the following criteria:

- **Exploratory Data Analysis (EDA)**: 25%
  - Quality and depth of the analysis, along with actionable insights derived from the data.
  
- **Business Insights**: 15%
  - Relevance, clarity, and impact of the business insights generated from the data.

- **Lookalike Model**: 30%
  - Accuracy, logic, and relevance of the lookalike model.
  - Quality of customer recommendations and similarity scores.

- **Customer Segmentation**: 30%
  - Clustering logic and metrics (e.g., DB Index).
  - Visual representation of clusters and segmentation results.

## Submission Instructions

1. **GitHub Submission**: Upload all the code files, PDF reports, and the README to a public GitHub repository.
2. **Share the GitHub Link**: Provide the GitHub link in your submission.

## Final Notes

This assignment will test your ability to extract insights from data, build predictive models, and apply clustering techniques. Be sure to focus on clean, efficient code and derive actionable insights that can be valuable to the business.

Good luck!
