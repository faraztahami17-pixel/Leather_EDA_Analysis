# Leather Manufacturing & Export — Exploratory Data Analysis

A classic **data analytics EDA project** (Jupyter Notebook) analysing a leather
manufacturing & export business in Tamil Nadu, India. Built as a Data Analytics
internship project for **A.S. Solutions**.

## 📓 What's inside

```
leather-eda/
├─ Leather_EDA_Analysis.ipynb   # the main notebook (run this)
├─ data/                         # 10 source CSV files
├─ requirements.txt
└─ README.md
```

## 🔎 What it covers

A standard end-to-end analysis workflow:

1. **Business understanding** — the questions we want to answer
2. **Data loading** — read all 10 CSVs
3. **Data inspection** — shapes, dtypes, summary stats, missing values, duplicates
4. **Data cleaning & preparation** — date parsing, feature engineering, joining
   Orders + Finance + Customers into one `sales` table
5. **Exploratory Data Analysis** across Sales, Production, Quality, Inventory,
   Shipment, Finance and Workforce, plus a correlation heatmap
6. **Key insights** (computed from the data)
7. **Conclusion & recommendations**
8. **Future work**

Charts use **matplotlib** and **seaborn**: line, bar, barh, pie, histogram,
box plot, scatter, Pareto and heatmap.

## ⚙️ How to run

```bash
cd leather-eda
pip install -r requirements.txt
jupyter notebook Leather_EDA_Analysis.ipynb
```

Then in Jupyter: **Kernel → Restart & Run All** to execute every cell top to
bottom. (You can also open the file in VS Code with the Jupyter extension, or
upload it to Google Colab — just upload the `data/` folder too.)

## 🛠 Tech stack

Python · pandas · numpy · matplotlib · seaborn · Jupyter

## 📊 Example insights produced

- Total revenue and profit margin across all orders
- Largest export market by revenue share
- Factory with the lowest average waste
- Overall quality pass rate and the top defects (Pareto 80/20)
- On-time delivery rate and the worst-performing port
- Largest cost component and count of inventory bins below reorder level
