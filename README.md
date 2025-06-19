# 🛍️ Black Friday Dataset Exploratory Data Analysis (EDA)

This project performs exploratory data analysis (EDA) on the **Black Friday Dataset** from a retail store, aiming to understand customer purchasing behavior and gain insights from the data. The dataset is commonly used for data preprocessing and analysis exercises.

## 📁 Dataset Overview

The dataset is sourced from [Kaggle: Black Friday Dataset](https://www.kaggle.com/datasets/sdolezel/black-friday) and contains customer demographics, product categories, and purchase amounts from a retail store on Black Friday.

### Features

| Feature               | Description                                                  |
|-----------------------|--------------------------------------------------------------|
| `User_ID`             | Unique ID for a user                                         |
| `Product_ID`          | Unique ID for a product                                      |
| `Gender`              | Gender of the user (`M`, `F`)                                |
| `Age`                 | Age group of the user                                        |
| `Occupation`          | Occupation code                                              |
| `City_Category`       | Category of the city (`A`, `B`, `C`)                         |
| `Stay_In_Current_City_Years` | Number of years stayed in the current city            |
| `Marital_Status`      | Marital status (`0`: single, `1`: married)                  |
| `Product_Category_1`  | Primary product category                                     |
| `Product_Category_2`  | Secondary product category                                   |
| `Product_Category_3`  | Tertiary product category                                    |
| `Purchase`            | Purchase amount (target variable)                           |

## 🔍 Objectives

- Understand the structure of the dataset
- Clean and preprocess the data
- Handle missing values
- Visualize data distributions and relationships
- Analyze customer and product trends

## 🧪 Steps Performed

### 1. Data Loading & Inspection
- Loaded dataset using `pandas`
- Examined shape, datatypes, and sample entries

### 2. Missing Values
- Identified missing values in `Product_Category_2` and `Product_Category_3`
- Filled missing values with mode or kept as-is depending on analysis goals

### 3. Data Cleaning
- Removed irrelevant features (`User_ID`, `Product_ID`) if necessary for group-wise analysis
- Converted categorical features into proper formats

### 4. Exploratory Data Analysis (EDA)
- Univariate analysis: Distribution plots for gender, age, city category, purchase, etc.
- Bivariate analysis: Relationship between purchase amount and other features
- Aggregated insights using `groupby` and `pivot_table`

### 5. Visualizations
- Bar plots for gender vs purchase
- Histograms for numerical fields
- Count plots for categorical features
- Box plots to detect outliers in `Purchase`

## 📈 Key Insights

- Males make more purchases than females
- Age group 26–35 forms the majority of buyers
- City Category B has the highest sales
- Product Category 1 dominates purchase behavior
- Significant number of missing values in secondary and tertiary product categories

## 🛠️ Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## ⚙️ How to Run

1. Clone the repository or download the `.ipynb` notebook.
2. Install required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn
