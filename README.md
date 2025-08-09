# 🛡️ Insurance Cost Analysis (Power BI)

Analytics project built **entirely in Power BI** — ETL in **Power Query**, modeling in the **Data Model**, and KPIs using **DAX**.  
The dashboard explores how **age, sex, BMI, children, region** affect **insurance charges**.

---

## 📂 Project Files
- **Power BI file (.pbix):** [insurance.pbix](https://github.com/Zahra2105/Insurance-/blob/main/insurance.pbix)
- **Source dataset (CSV):** [insurance.csv](https://github.com/Zahra2105/Insurance-/blob/main/insurance.csv)
- **Preview images:**  
  ![Preview 1](https://github.com/Zahra2105/Insurance-/blob/main/1.png)  
  ![Preview 2](https://github.com/Zahra2105/Insurance-/blob/main/2.png)  
  ![Preview 3](https://github.com/Zahra2105/Insurance-/blob/main/3.png)  
  ![Preview 4](https://github.com/Zahra2105/Insurance-/blob/main/4.png)

---

## 🧩 Data Modeling & ETL (Inside Power BI)
- **Power Query**  
  - Load CSV, detect data types, clean nulls, format text columns (sex, region)
- **Data Model**  
  - Single fact table (insurance dataset)  
  - Added **Date Table** for time-based slicers (if required)
- **DAX (Measures & Calculated Columns)**  
  - `Avg Charges`  
  - `BMI Category` (Underweight, Normal, Overweight, Obese)  
  - `Total Children` by region/sex  
  - `Charges per Child`  
  - KPI cards and % comparisons

---

## 📈 Dashboard Highlights
- **Demographic Analysis:** charges by age groups, gender, region  
- **BMI Impact:** correlation between BMI category & charges  
- **Family Size Effect:** children count vs. average charges  
- **Regional Breakdown:** average BMI & charges by region  
- Interactive slicers for **sex**, **region**, **BMI category**

---

## 🛠 Stack
- **Power BI** (Power Query, Data Model, **DAX**)
- **CSV** dataset from public source (Kaggle)

---

## 🔒 Confidentiality
Dataset is public; no proprietary company data is included.

---

## ▶️ How to Open
1. Download/clone the repo.  
2. Open `insurance.pbix` in **Power BI Desktop**.  
3. If prompted, repoint the data source to `./insurance.csv`.  
4. Refresh to rebuild visuals and measures.
