# Housing Data Analysis & Visualization

Exploratory data analysis of **545 house listings** to understand what drives house prices — location, size, air-conditioning, parking and furnishing — presented through clear charts and grouped comparisons.

> Minor Project — Data Science Internship at **Elewayte** (Internship Partner: Cubestech)

![Python](https://img.shields.io/badge/Python-3.x-blue) ![pandas](https://img.shields.io/badge/pandas-Data%20Analysis-orange) ![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-green) ![Seaborn](https://img.shields.io/badge/Seaborn-Charts-teal)

## Dataset

- **File:** `Housing.csv` (included in this repo)
- **Size:** 545 houses × 13 attributes
- **Attributes:** price, area, bedrooms, bathrooms, stories, mainroad, guestroom, basement, hotwaterheating, airconditioning, parking, prefarea, furnishingstatus

## Key Findings

- **₹26–50 Lakhs is the largest price segment** — 318 of 545 houses (58%). The next bands are ₹51–75 Lakhs (148 houses), ₹76–100 Lakhs (39), above ₹100 Lakhs (8) and ₹0–25 Lakhs (32).
- **Air-conditioning adds ~43% to the average price** — AC homes averaged **₹60.1 Lakhs** vs **₹41.9 Lakhs** for non-AC homes.
- **Parking pays off** — average price rises from **₹41.4 Lakhs** (no parking) to **₹59.0 Lakhs** (2 parking spaces).
- **Preferred-area + size gap is ₹27.2 Lakhs** — large houses in preferred areas averaged **₹65.5 Lakhs** vs **₹38.3 Lakhs** for smaller houses elsewhere.

## What the Notebook Does

1. Loads and inspects the dataset (shape, data types, summary statistics)
2. Converts prices to Lakhs and groups houses into price bands
3. Compares segments with `groupby` — air-conditioning, parking, preferred area, furnishing
4. Visualizes results with line, bar and scatter charts (Matplotlib & Seaborn)

## Files

| File | Description |
|---|---|
| `Housing_Data_Analysis_and_Visualization.ipynb` | Main analysis notebook with outputs and charts |
| `Housing.csv` | Dataset (545 rows) |
| `requirements.txt` | Python dependencies |

## How to Run

```bash
pip install -r requirements.txt
jupyter notebook Housing_Data_Analysis_and_Visualization.ipynb
```

The notebook reads `Housing.csv` from the same folder.

## Tools Used

Python · pandas · NumPy · Matplotlib · Seaborn · Jupyter / Google Colab

## Author

**Kushal Rawat** — Data Analyst | BCA (AI & Data Science), JECRC University, Jaipur
[LinkedIn](https://www.linkedin.com/in/kushal-rawat-data/) · [GitHub](https://github.com/kushalrawat2005-19)
