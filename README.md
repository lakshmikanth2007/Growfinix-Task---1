# Growfinix-Task---1
# 🏠 Real Estate Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on a real estate dataset using Python. The objective is to clean messy housing data, handle missing values and outliers, and generate visualizations to understand how different property features affect house prices.

This project was completed as part of a Data Science Internship (Task 1).

---

## 🎯 Objectives

- Load and inspect the dataset
- Identify and handle missing values
- Remove duplicate records
- Clean unnecessary columns
- Handle outliers using the IQR method
- Export the cleaned dataset
- Create visualizations to analyze property prices and relationships between variables

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📂 Dataset

The project uses the **Melbourne Housing Dataset** (`melb_data.xlsx`).

The dataset contains information such as:

- Property Price
- Number of Rooms
- Land Size
- Council Area
- Year Built
- Car Spaces
- Property Type
- Address
- Suburb
- And other housing-related features

---

## 🧹 Data Cleaning Process

The following preprocessing steps were performed:

### 1. Data Inspection

- Viewed the first few rows
- Checked dataset information
- Generated descriptive statistics

### 2. Missing Value Handling

- Calculated missing value percentages.
- Removed the **BuildingArea** column because it contained a large number of missing values.
- Filled missing values in **CouncilArea** using the mode.
- Filled missing values in **Car** using the mean.
- Removed rows with missing **YearBuilt** values.
- Removed any remaining rows containing missing values.

### 3. Duplicate Removal

Duplicate records were removed to improve data quality.

### 4. Outlier Detection

Outliers were removed using the **Interquartile Range (IQR)** method for:

- Price
- Landsize

---

## 📊 Visualizations

The notebook includes the following visualizations:

### 1. Price Distribution

Histogram showing the distribution of house prices.

**Purpose:**
- Understand price spread
- Detect skewness

---

### 2. Top Property Prices (Bar Chart)

Bar chart of the first 10 properties after sorting by price.

**Purpose:**
- Compare property prices

---

### 3. Land Size vs Price

Scatter plot showing the relationship between land size and property price.

**Purpose:**
- Analyze whether larger properties tend to cost more

---

### 4. Correlation Heatmap

Displays correlation among all numerical features.

**Purpose:**
- Identify strongly related variables

---

### 5. Rooms vs Price

Box plot comparing property prices across different numbers of rooms.

**Purpose:**
- Study how room count affects price
- Detect outliers within each room category

---

### 6. Average Price by Rooms

Line chart showing the average house price for each room count.

**Purpose:**
- Observe price trends as the number of rooms increases

---

## 📤 Output

The cleaned dataset is exported as:

cleaned_data.xlsx

---

## 📈 Key Data Cleaning Techniques Used

- Missing value analysis
- Mean imputation
- Mode imputation
- Duplicate removal
- Column removal
- IQR-based outlier removal
- Data export to Excel

---

## 📚 Learning Outcomes

Through this project, the following concepts were practiced:

- Data cleaning
- Handling missing values
- Feature preprocessing
- Outlier detection
- Exploratory Data Analysis (EDA)
- Data visualization
- Exporting cleaned datasets
- Working with real-world housing data

---


**Lakshmikantha Reddy**

Data Science Intern

---
