# 🎯 Power BI Data Cleaning – Netflix Dataset

This Power BI project showcases a clean and structured approach to preparing raw data using **Power Query Editor**. The dataset originally contained several inconsistencies, missing values, and formatting issues that were resolved to ensure accurate analysis and visualization.

---

## 🧹 Data Cleaning Steps Performed

The following transformations and cleaning operations were performed using **Power Query in Power BI**:

1. **Removed Duplicate Records**  
   - Used the **Remove Duplicates** feature to eliminate repeated rows and ensure uniqueness in the dataset.

2. **Handled Missing Director Values**  
   - Replaced all **blank (null)** values in the `director` column with `"Unknown"` using the **Replace Values** transformation.

3. **Filtered Out Unnecessary Rows**  
   - Removed an entire table consisting of a **single null entry** using the **Filter** option to maintain data relevance.

4. **Corrected Country Name Format**  
   - Used **Find and Replace** to correct wrongly formatted entries in the `country` column (e.g., trimming whitespaces, fixing inconsistent cases or punctuation).

5. **Standardized Data Types**  
   - Ensured that each column had the correct **data type** assigned (e.g., text, date, number) for proper aggregation and visualization in Power BI.

---

## 📁 File Included

- `Task 1 solutions.pbix` – The cleaned Power BI project file ready for analysis or visualization.

---

## 🧠 Purpose

This project demonstrates the use application essential for **data cleaning techniques** using Power BI — a crucial step before conducting any analysis. It's designed to highlight real-world data preparation challenges and their solutions.

---

## 🚀 How to Use

1. Clone this repository or download the `.pbix` file.
2. Open the file using **Power BI Desktop**.
3. Review the **Power Query Editor** to inspect each transformation step.
---
## 💡 Tools Used

- Power BI Desktop
- Power Query Editor

---

