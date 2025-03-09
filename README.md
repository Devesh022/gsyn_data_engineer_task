# GSynergy Data Engineer Task

## 🚀 Project Overview
This project processes raw sales data and transforms it into an aggregated data warehouse.

## 📂 ELT Pipeline Overview
- **Bronze Layer:** Raw data ingestion
- **Silver Layer:** Data cleansing & normalization
- **Gold Layer:** Aggregated weekly sales reporting

## 🛠️ Technologies Used
- **Databricks (Community Edition)**
- **PySpark (Spark SQL)**
- **Azure Blob Storage (FileStore)**
- **Databricks Tables (Delta)**

## ⚡ How to Run
1. **Upload the `.gz` files** to Databricks FileStore
2. **Run the notebook** (Bronze, Silver, Gold)
3. **Check results** using SQL queries

## 📊 Key Outputs
- `retail_dw.silver_transactions`
- `retail_dw.silver_averagecosts`
- `retail_dw.mview_weekly_sales`

## ER Daigram
![ER Daigram](https://github.com/Devesh022/gsyn_data_engineer_task/blob/main/Gsynergy/Gsyn_task_ER_Daigram.png) 

## Dataset
**Find the dataset using Link:**
  https://drive.google.com/drive/folders/14y-FqE3Kq4yCH1nc65TesIKjq13KOCnk?usp=sharing

## 📝 Author
- **Devesh Premani**
