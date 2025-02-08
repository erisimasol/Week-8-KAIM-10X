<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Week-08-Task-01.ipynb</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 20px;
        }
        h1, h2, h3 {
            color: #2c3e50;
        }
        code {
            background-color: #f4f4f4;
            padding: 2px 5px;
            border-radius: 3px;
            font-family: monospace;
        }
        pre {
            background-color: #f4f4f4;
            padding: 10px;
            border-radius: 5px;
            overflow-x: auto;
        }
        .section {
            margin-bottom: 30px;
        }
        .section h2 {
            border-bottom: 2px solid #2c3e50;
            padding-bottom: 5px;
        }
        .section p {
            margin-top: 10px;
        }
    </style>
</head>
<body>
    <h1>Week-08-Task-01.ipynb</h1>
    <p>This Jupyter notebook file contains code and analysis related to Week 8, Task 1. The notebook focuses on data analysis using Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn. The dataset used in this notebook is related to fraud detection, and the notebook includes various data exploration and visualization tasks.</p>

    <div class="section">
        <h2>Notebook Overview</h2>
        <p>The notebook is structured as follows:</p>
        <ul>
            <li><strong>Importing Libraries:</strong> The notebook starts by importing necessary Python libraries such as Pandas, NumPy, Matplotlib, Seaborn, and others.</li>
            <li><strong>Loading the Dataset:</strong> The dataset is loaded from a CSV file located at <code>C:\Users\pc\Desktop\KAIM10X\Fraud_Data.csv</code>.</li>
            <li><strong>Data Exploration:</strong> The notebook provides an overview of the dataset, including basic statistics, missing value checks, and summary statistics for various columns such as <code>purchase_value</code>, <code>age</code>, <code>sex</code>, <code>signup_time</code>, <code>purchase_time</code>, and <code>source</code>.</li>
            <li><strong>Data Visualization:</strong> The notebook includes visualizations such as histograms for <code>purchase_value</code> and <code>age</code> to understand the distribution of these variables.</li>
            <li><strong>Missing Value Check:</strong> The notebook checks for missing values in the dataset and confirms that there are no missing values in any of the columns.</li>
        </ul>
    </div>

    <div class="section">
        <h2>Key Features</h2>
        <ul>
            <li><strong>Data Loading:</strong> The dataset is loaded using Pandas, and the first few rows are displayed to get a quick look at the data.</li>
            <li><strong>Data Summary:</strong> The notebook provides a detailed breakdown of the dataset, including the number of entries, data types, and summary statistics for numerical columns.</li>
            <li><strong>Visualizations:</strong> The notebook uses Matplotlib and Seaborn to create visualizations that help in understanding the distribution of key variables.</li>
            <li><strong>Missing Value Analysis:</strong> The notebook checks for missing values in the dataset and confirms that the dataset is complete.</li>
        </ul>
    </div>

    <div class="section">
        <h2>Usage</h2>
        <p>To use this notebook, ensure that you have the necessary Python libraries installed. You can install them using pip:</p>
        <pre><code>pip install pandas numpy matplotlib seaborn</code></pre>
        <p>Once the libraries are installed, you can open the notebook in Jupyter and run the cells sequentially to reproduce the analysis.</p>
    </div>

    <div class="section">
        <h2>Dataset</h2>
        <p>The dataset used in this notebook is a fraud detection dataset containing various features such as <code>user_id</code>, <code>signup_time</code>, <code>purchase_time</code>, <code>purchase_value</code>, <code>device_id</code>, <code>source</code>, <code>browser</code>, <code>sex</code>, <code>age</code>, <code>ip_address</code>, and <code>class</code>. The <code>class</code> column indicates whether a transaction is fraudulent (1) or not (0).</p>
    </div>

    <div class="section">
        <h2>Conclusion</h2>
        <p>This notebook provides a comprehensive analysis of a fraud detection dataset. It covers data loading, exploration, visualization, and missing value checks. The insights gained from this analysis can be used to build predictive models for fraud detection.</p>
    </div>

    <div class="section">
        <h2>References</h2>
        <ul>
            <li><a href="https://pandas.pydata.org/">Pandas Documentation</a></li>
            <li><a href="https://numpy.org/">NumPy Documentation</a></li>
            <li><a href="https://matplotlib.org/">Matplotlib Documentation</a></li>
            <li><a href="https://seaborn.pydata.org/">Seaborn Documentation</a></li>
        </ul>
    </div>
</body>
</html>