# Analyzing Last.fm Dataset Using PySpark in Google Colab

## Overview
In this project, we will use the **PySpark** module in Python to analyze a dataset from Last.fm, an online music service where users can listen to various songs. The dataset consists of two CSV files:

- `listening.csv`: Contains data about user listening habits.
- `genre.csv`: Contains information about music genres.

Our goals are to:
1. Apply queries to the dataset using PySpark.
2. Visualize query results with **matplotlib**.

## Tools and Environment
We will use **Google Colab** as the development environment. Google Colab is ideal for running PySpark code without requiring a local setup. 

## Steps
1. **Setting Up PySpark in Google Colab**: 
   - Install PySpark and set up the environment.
2. **Loading the Dataset**:
   - Import and load the `listening.csv` and `genre.csv` files into Spark DataFrames.
3. **Applying Queries**:
   - Use PySpark SQL or DataFrame operations to analyze the data.
4. **Visualization**:
   - Use **matplotlib** to visualize the query results.

## Libraries Required
```bash
pip install pyspark matplotlib
