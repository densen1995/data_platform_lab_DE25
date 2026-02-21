# data_platform_lab_DE25

##  Project Overview
**Using Pandas to Extract, Transform and load data. (ETL pipeline)**

---

**Basically we will:**
- Read the CSV (product.csv)
- Clean and Transform it using pandas in python
    - Reject impossible values and validate dataset(df_valid). If a row is impossible it shouldn't be flagged , rather it should already be removed.
    - Flag suspicious values(but can be usable)
- Generate analytics reports( outputs/files) exported as csv files like; analytics_summary.csv(which aggregates average, median, quantity of products etc), price_analysis(detect statistical outliers using Z-score), and rejected_products.csv

---

## Project Structure
price-validation-analysis/
│
├── data/
│   ├── raw/
│   │   └── products.csv
│   │
│   └── output/
│       ├── analytics_summary.csv
│       ├── price_analysis.csv
│       └── rejected_products.csv
│
├── main.ipynb
│
│
├── docs/
│   └── theory.md
│
├── requirements.txt
├── README.md
└── .gitignore

---


**Summary**
- Raw -> Reject -> Valid -> Flag -> Analytics

##Technologies used 
- Python
- Pandas 
- Matplotlib

**Guide**
- Installera och aktivera en virtual enviroment.
- Installera packages/dependencies(t.ex pandas , ipykernel) och Importera bibliotek somm behövs t.ex, pandas. Note:(ipykernel endast för jupiter notebook anvädning)
- Installera och importera matplotlib for plotting (*bonus*).

---




