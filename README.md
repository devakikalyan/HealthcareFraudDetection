# Healthcare Fraud Detection

### GROUP NAME: TEAM HECTOR
###  Group Number: 22

Devaki Kalyan Chandra Yadav Podila, SID: 862468795   Email: pyada015@ucr.edu

Rohith Reddy Kancharakuntla, SID: 862466402  Email: rkanc004@ucr.edu 

Shubham Mishra, SID: 862467767  Email: smish040@ucr.edu

Omkar Kadam, SID: 862467471  Email: okda001@ucr.edu 

Yash Kathe, SID: 862464930 , Email: ykath001@ucr.edu 

## Instructions

This Jupyter Notebook contains code for Healthcare fraud detection using Spark and PySpark.


## Overview

The notebook performs the following tasks:
- Setup: Install necessary dependencies and set up a Spark session.
- Data Preprosessing: Evaluate the three different datasets and combine data with joins.
- Feature Extraction and Engineering: Check for null values and explore the distribution of classes (fraudulent and non-fraudulent cases).
- Machine Learning: Use different machine learning algorithms (Logistic Regression, Random Forest, Naive Bayes, Gradient Boosting) for fraud detection.
- Model Evaluation: Evaluate the models using accuracy, F1 score and AUC Score.

## Prerequisites

Before running the code, make sure you have the following prerequisites installed:
- Java Development Kit (JDK) 8
- Apache Spark
- Python with required libraries (pyspark)

## Usage

### Compilation and Execution
1. Ensure that Java 8 is installed on your system.
2. Install PySpark by running the following command:
    ```bash
    !pip install pyspark
    ```

3. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/...../HealthCareFraudDetection.git
    ```
    **OR**

3. Download the project as a .zip or .tar.gz file
    - Extract the downloaded file to your local machine.

4. Run the code in a Python environment (e.g., Jupyter Notebook, Colab) that supports PySpark.

### Setting up Spark on Colab

```python
# Install Java and PySpark
!apt-get install openjdk-8-jdk-headless -qq > /dev/null
!pip install pyspark

# Import necessary libraries
from pyspark.sql import SparkSession

# Create a Spark session
spark = SparkSession.builder.appName("HealthCareModel").getOrCreate()

# Load the dataset
file_path = ""
df = spark.read.csv(file_path, header=True, inferSchema=True)

# Explore the dataset
df.printSchema()
```

### Author Contributions

- **DEVAKI KALYAN CHANDRA YADAV PODILA:**
  - Finding the dataset
  - Literature Survey
  - Data pre-processing
  - Understanding the part-d prescriber by providerad drug dataset
  - Understanding payment dataset
  - Understanding list of excluded individual dataset
  - Transforming datatype of columns
  - Joining Datasets on NPI
  - Training and Testing ML Models
  - Data visualization
  - Conducted exploratory data analysis.

- **ROHITH REDDY KANCHARLAKUNTLA:**
  - Finding the dataset
  - Literature Survey
  - Data pre-processing
  - Understanding the part-d prescriber by providerad drug dataset
  - Understanding payment dataset
  - Understanding list of excluded individual dataset
  - Transforming datatype of columns
  - Joining Datasets on NPI
  - Training and Testing ML Models
  - Data visualization
  - Conducted exploratory data analysis.

- **SHUBHAM MISHRA:**
  - Finding the dataset
  - Literature Survey
  - Data pre-processing
  - Understanding the part-d prescriber by providerad drug dataset
  - Understanding payment dataset
  - Understanding list of excluded individual dataset
  - Transforming datatype of columns
  - Joining Datasets on NPI
  - Training and Testing ML Models
  - Data visualization
  - Conducted exploratory data analysis.

- **OMKAR KADAM:**
  - Finding the dataset
  - Literature Survey
  - Data pre-processing
  - Understanding the part-d prescriber by providerad drug dataset
  - Understanding payment dataset
  - Understanding list of excluded individual dataset
  - Transforming datatype of columns
  - Joining Datasets on NPI
  - Training and Testing ML Models
  - Data visualization
  - Conducted exploratory data analysis.

- **YASH KATHE:**
  - Finding the dataset
  - Literature Survey
  - Data pre-processing
  - Understanding the part-d prescriber by providerad drug dataset
  - Understanding payment dataset
  - Understanding list of excluded individual dataset
  - Transforming datatype of columns
  - Joining Datasets on NPI
  - Training and Testing ML Models
  - Data visualization
  - Conducted exploratory data analysis.




