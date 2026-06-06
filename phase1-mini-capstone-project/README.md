# Codeboosters Phase 1 Capstone Project

## Data Engineering Phase — Student Pass-Fail Analysis System

---

## Project Overview

This project is developed as part of the **Codeboosters Tech Phase 1 Capstone Project** for the **Data Engineering Phase**. The objective of this project is to design and implement a complete end-to-end data engineering workflow using Python, SQL, Pandas, PySpark, and Machine Learning techniques.

The project uses a **Student Pass-Fail Dataset** to perform data ingestion, preprocessing, SQL analysis, ETL pipeline implementation, PySpark Medallion Architecture, data visualization, and predictive machine learning modeling.

The complete project has been implemented in a **single Jupyter Notebook** as per the project requirements.

---

# Objectives

* Perform data ingestion using Pandas
* Analyze dataset structure and quality
* Clean and preprocess the dataset
* Integrate SQLite database operations
* Execute SQL analytical queries
* Build SQL-based transformed datasets
* Implement a structured ETL pipeline
* Design Bronze, Silver, and Gold layers using PySpark
* Compare CSV and Parquet file formats
* Create meaningful visualizations
* Train and evaluate a Machine Learning model

---

# Dataset Information

### Dataset Name

Student Pass-Fail Dataset

### Dataset Features

| Column Name          | Description                    |
| -------------------- | ------------------------------ |
| student_id           | Unique student identifier      |
| attendance_pct       | Attendance percentage          |
| homework_pct         | Homework completion percentage |
| midterm_score        | Midterm examination score      |
| study_hours_per_week | Average weekly study hours     |
| pass                 | Student pass/fail status       |

---

# Technologies Used

| Technology   | Purpose                                        |
| ------------ | ---------------------------------------------- |
| Python       | Core programming language                      |
| Pandas       | Data ingestion and preprocessing               |
| SQLite       | Database integration and SQL queries           |
| PySpark      | Big data processing and Medallion Architecture |
| Matplotlib   | Data visualization                             |
| Scikit-learn | Machine Learning model training                |
| Google Colab | Development environment                        |

---

# Project Workflow

## 1. Data Ingestion

The CSV dataset was loaded into a Pandas DataFrame for analysis. Dataset structure, shape, data types, missing values, and duplicate records were examined.

---

## 2. Data Cleaning and Preprocessing

The dataset was cleaned by:

* Removing duplicate records
* Handling missing values
* Standardizing column names
* Preparing the dataset for analysis and machine learning

The cleaned dataset was exported as a separate CSV file.

---

## 3. SQLite Database Integration

The processed dataset was integrated into a SQLite database to perform SQL-based analysis and transformations.

Operations performed:

* Database creation
* Table insertion
* Record verification
* Query execution

---

## 4. SQL Analysis

Various SQL queries were implemented including:

* Filtering queries
* Sorting operations
* Aggregation functions
* Group By analysis
* Conditional CASE statements

---

## 5. SQL-Based Data Transformation

Additional derived columns were created using SQL logic and CASE statements to generate business-oriented insights.

Examples:

* Attendance category
* Study hour category
* Performance classification

---

# ETL Pipeline

A complete ETL (Extract, Transform, Load) pipeline was implemented.

## Extract

Raw data was extracted from the CSV source file.

## Transform

The dataset was cleaned, standardized, and transformed.

## Load

The transformed dataset was exported into a new output CSV file.

---

# PySpark Medallion Architecture

The Medallion Architecture was implemented using PySpark to organize the data into multiple processing layers.

## Bronze Layer

* Raw ingested dataset
* Stored in Parquet format
* Maintains original source data

## Silver Layer

* Cleaned and standardized dataset
* Duplicate and null records removed
* Optimized for transformation

## Gold Layer

* Business-ready aggregated datasets
* KPI generation and analytical summaries
* Used for reporting and insights

---

# CSV vs Parquet Comparison

The project compares CSV and Parquet formats based on:

* File size
* Storage efficiency
* Read/write performance
* Advantages and limitations

The analysis demonstrates how Parquet provides better storage optimization and faster processing for large-scale data engineering workflows.

---

# Data Visualization Dashboard

A multi-visualization dashboard was created using Matplotlib containing:

* Bar Chart
* Pie Chart
* Line Graph
* Horizontal Bar Chart

The dashboard provides insights into:

* Pass vs fail distribution
* Study hour patterns
* Midterm score trends
* Top-performing students

---

# Machine Learning Model

A Random Forest Classification model was trained using the processed dataset to predict whether a student would pass or fail.

## Machine Learning Workflow

* Feature selection
* Label encoding
* Train-test split
* Model training
* Prediction generation
* Accuracy evaluation

The model demonstrates how academic performance indicators can be used for predictive analytics.

---

# Project Folder Structure

```bash
Codeboosters-Phase1-Capstone-Project/
│
├── Phase1_capstone_project.ipynb
├── Pass-Fail Data.csv
├── cleaned_pass_fail_dataset.csv
├── transformed_student_dataset.csv
├── etl_output.csv
├── pass_fail_database.db
├── bronze_layer.parquet/
├── silver_layer.parquet/
├── gold_layer.parquet/
└── README.md
```

---

# Key Learnings

Through this project, the following concepts were successfully implemented and understood:

* Real-world data engineering workflow
* Data preprocessing techniques
* SQL analytical operations
* ETL pipeline design
* Big data architecture concepts
* PySpark processing
* Parquet file optimization
* Data visualization techniques
* Machine learning model development

---

# Conclusion

This project successfully demonstrates a complete end-to-end Data Engineering lifecycle using modern tools and technologies. The implementation covers data ingestion, cleaning, SQL processing, ETL pipelines, PySpark Medallion Architecture, visualization, and machine learning within a single integrated workflow.

The project highlights how data engineering and analytics techniques can be combined to transform raw educational data into meaningful insights and predictive intelligence.

---

# Author

**Oviya Raj**
Artificial Intelligence and Data Science (AIDS)

Codeboosters Tech — Phase 1 Capstone Project
