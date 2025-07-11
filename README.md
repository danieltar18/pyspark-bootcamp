# PySpark Bootcamp

Hands-on PySpark bootcamp with Jupyter notebooks covering the foundations of Apache Spark using PySpark. This bootcamp is based on real-world use cases and designed for data analysts and engineers transitioning from SQL or Pandas to distributed data processing.

📘 **Tutorial Source:**  
This project is based on [coder2j/pyspark-tutorial](https://github.com/coder2j/pyspark-tutorial?tab=readme-ov-file#introduction).

## 📂 Structure

The repository contains a sequence of notebooks that walk you through PySpark concepts step by step:

| Notebook | Topic |
|----------|-------|
| `01-Get-Started.ipynb` | Environment setup, PySpark basics |
| `02-SparkContext.ipynb` | Introduction to SparkContext |
| `03-SparkSession.ipynb` | Creating and using SparkSession |
| `04-RDD-Operations.ipynb` | RDD fundamentals and transformations |
| `05-DataFrames.ipynb` | DataFrame creation and basic usage |
| `06-DataFrames-Various-Sources.ipynb` | Reading data from multiple sources (CSV, JSON, Parquet) |
| `07-DataFrame-Operations.ipynb` | Common DataFrame transformations and actions |
| `08-Spark-SQL.ipynb` | Using SQL syntax within Spark |

📁 The `data/` folder contains sample datasets used in the notebooks.

## 🛠️ Requirements

- Python 3.x
- Apache Spark
- Jupyter Notebook or JupyterLab

To install the required packages:
```bash
pip install pyspark notebook
