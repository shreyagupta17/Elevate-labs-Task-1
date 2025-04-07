🧹 Elevate Labs - Task 1: Marketing Campaign Data Cleaning Project  
This project is all about transforming a **raw, messy dataset** into a clean, analysis-ready format. The dataset (`marketing_campaign_dirty.csv`) includes valuable information about customer demographics and their responses to marketing campaigns.

---

## 🗂️ Dataset Overview

The original dataset had several data quality issues:

- ❌ Missing or null values  
- 🔁 Duplicate rows  
- 🔡 Inconsistent text formatting  
- 🗓️ Unstandardized date formats  
- 🧾 Improper column naming  
- 🔢 Incorrect data types  

---

## ✅ Cleaning Steps Performed

### 1️⃣ Handling Missing Values
- Replaced **null/empty values** with:
  - `0` for **numerical** columns  
  - `"Unknown"` for **categorical** columns

### 2️⃣ Removing Duplicates
- Deleted **duplicate rows** to maintain **data accuracy and uniqueness**

### 3️⃣ Text Standardization
- Cleaned and standardized fields like:
  - **Education** (`graduation` ➝ `Graduation`)
  - **Marital_Status** (`single`, `Single` ➝ `Single`)

### 4️⃣ Date Format Conversion
- Unified all date formats to: `dd-mm-yyyy`

### 5️⃣ Renaming Columns
- Made column headers:
  - Lowercase  
  - Without spaces or special characters  
  - Underscore-separated  
  - Example: `Year Of Birth` ➝ `year_of_birth`

### 6️⃣ Fixing Data Types
- Converted:
  - `age` ➝ `int`  
  - Dates ➝ `datetime`  
  - Other fields ➝ **appropriate types**

---

## 🛠️ Tools Used

- 📊 **Advanced Excel**

---

## 🔮 Future Work

- 🔍 Perform **Exploratory Data Analysis (EDA)**  
- 📈 Build **visualizations** for insights  
- 🤖 Train **machine learning models** to enhance marketing strategy

