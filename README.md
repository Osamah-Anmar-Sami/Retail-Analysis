# Retail Data Analysis

## 1. Overview

This project focuses on **Data Curation and Exploratory Data Analysis (EDA)** using Python and Tableau on retail transactional data for multiple countries.

The data curation process involves handling missing values, removing duplicates, correcting data types, renaming columns, creating new features, and improving data consistency to prepare the dataset for analysis.

The EDA process applies Univariate, Bivariate, and Multivariate Analysis to identify patterns, relationships, trends, and meaningful insights related to customers, products, transactions, and retail performance.

## 2. Project Objectives

- Improve data quality through data curation and preprocessing.
- Explore customer and transactional data.
- Identify patterns and relationships between variables.
- Explore product and category performance.
- Compare retail performance across multiple countries.
- Discover meaningful trends and insights.
- Present analytical findings through interactive Tableau dashboards.

## 3. Tools & Technologies

**Programming Language:**
- Python

**Libraries:**
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Colorcet

**Data Visualization:**
- Tableau

**Development Environment:**
- Jupyter Notebook

## 4. Dataset

The dataset represents retail transactional data containing information about customers, purchases, products, and transaction details across five countries:

- United States (USA)
- United Kingdom (UK)
- Canada
- Germany
- Australia

**Dataset Source:** [Retail Analysis Large Dataset – Kaggle](https://www.kaggle.com/datasets/sahilprajapati143/retail-analysis-large-dataset/data)

**Dataset Description:**

The dataset includes customer demographics, transaction information, product details, purchasing behavior, and other retail-related attributes.

**Data Source Disclaimer:**

The dataset was obtained from Kaggle. Its underlying records are not independently verified as actual retail transactions and should not be interpreted as confirmed real-world business data.

## 5. Project Workflow

### 5.1 Data Curation

Data curation and preprocessing were performed using Python and Pandas to improve data quality and consistency.

Key activities include:

- Handling missing values.
- Removing duplicate records.
- Correcting data types.
- Renaming columns.
- Creating new features.
- Reviewing data consistency.
- Identifying and addressing data quality issues.
- Preparing the cleaned dataset for further analysis.

### 5.2 Exploratory Data Analysis (EDA)

Exploratory Data Analysis was conducted to understand the dataset and uncover meaningful patterns and relationships.

The analysis includes:

**Univariate Analysis**
- Analyzing individual variables and their distributions.
- Exploring numerical and categorical features.
- Identifying outliers and unusual values.

**Bivariate Analysis**
- Exploring relationships between two variables.
- Comparing customer and purchasing characteristics.
- Examining relationships between products, transactions, and other variables.

**Multivariate Analysis**
- Investigating relationships between multiple variables.
- Exploring purchasing patterns across different customer and product groups.
- Identifying patterns and potential relationships within the dataset.

## 6. Tableau Dashboard

Interactive dashboards were developed using Tableau to present analytical findings and explore retail data across multiple countries.

**Dashboard:** [View Interactive Tableau Dashboard](https://public.tableau.com/views/AnalysisMultipleCountriesRetailData/AnalysisRetail?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## 7. Repository Structure

```text
Retail-Analysis/
│
├── DataCuration.ipynb
├── EDA.ipynb
├── README.md
├── LICENSE
└── Dataset/
```

## 8. Installation & Usage

### Prerequisites

- Python 3.x
- Jupyter Notebook

### Clone the Repository

```bash
git clone https://github.com/Osamah-Anmar-Sami/Retail-Analysis.git
```

### Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn colorcet
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

### Run the Notebooks

Execute the notebooks in the following order:

1. **DataCuration.ipynb** – Perform data cleaning, preprocessing, and feature creation.
2. **EDA.ipynb** – Perform Exploratory Data Analysis on the prepared dataset.

## 9. Key Areas of Analysis

The project explores several aspects of retail data:

- Customer Demographics and Purchasing Behavior.
- Product and Category Analysis.
- Transactional Analysis.
- Geographic and Country-Level Analysis.
- Relationships and Patterns Across Variables.

## 10. Project History

The original version of this project was completed in 2025, including data cleaning, Exploratory Data Analysis, and Tableau dashboard development.

The project is being further reviewed and improved to address additional data quality issues and enhance the analytical process.

## 11. License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
