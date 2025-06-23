# TASK-1
# 🧼 Sales Data Cleaning

This project is part of a data cleaning task using a sample sales dataset from Kaggle.

## 📁 Dataset

- Dataset name: **Sales Data Sample**
- Source: [Kaggle - Sample Sales Data](https://www.kaggle.com/datasets/kyanyoga/sale_data_sample)
- Files included:
  - `sales_data_sample.csv` (raw dataset)
  - `cleaned_sales_data.csv` (final cleaned output)
  - `DATA_CLEANING.ipynb` (code used in Jupyter)

## 🔧 Data Cleaning Steps

1. **Loaded the dataset** using `pandas.read_csv()` with `encoding='latin1'` to handle special characters.
2. **Cleaned column names**:
   - Stripped whitespace
   - Replaced spaces with underscores for consistency
3. **Handled null values**:
   - Dropped rows only if they had missing critical fields 
4. **Standardized text values**:
   - Converted all values in `country` column to UPPERcase
5. **Converted data types**:
   - `priceeach` → float
   - `quantityordered` → int
6. **Formatted dates**:
   - Formatted `ORDERDATE`as `yyyy-mm-dd`
7. **Dropped duplicates** 
8. **Saved the final cleaned DataFrame** to a new CSV file

---

## ✅ Output

- Cleaned dataset with consistent formatting and ready for further analysis or visualization.
- Total rows preserved: 147

---

## 🛠 Tools Used

- Python
- Pandas
- Jupyter Notebook
