# DataWarehouse_Project

## Dataset

The dataset used for this project is available on Kaggle at the following link:  
🔗 [Kaggle Dataset](https://www.kaggle.com/)

## Project Structure

The project is organized into the following directories:

### 📁 `documents/`

This folder contains all files related to the **design phase** of the data warehouse, including:

- Entity-Relationship diagrams
- Dimensional modeling documents
- Notes and specifications used during development

Although these materials are also summarized in the final report, the original files are provided here for completeness.

Additionally, this folder includes an **Excel file** containing **Data Quality Index tables**, which detail the metrics and indicators evaluated during the project.

---

### 📁 `code/`

This directory includes the core Jupyter notebooks used throughout the development process:

- **`preprocessing.ipynb`**  
  Contains the **data cleaning and preprocessing** logic applied before loading data into the reconciled database.

- **`etl.ipynb`**  
  Contains the complete **ETL (Extract, Transform, Load)** pipeline that moves and transforms the data from the raw layer to the final data warehouse schema.

- **`dataQuality.ipynb`**  
  Includes all **functions, validation rules**, and code used to **compute data quality indices**, such as precision, consistency, completeness.

---

### 📁 `db_dumps/`

This folder contains the **database dumps** of the two main databases created:

- The **reconciled database**
- The **data warehouse**

These can be used to restore the full database environments locally for testing or exploration purposes.
