# UAE Vehicle Market Analysis

[![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)](https://python.org)
[![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com)
[![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)](https://scikit-learn.org)
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)](https://pandas.pydata.org)
[![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=flat)](#)

Market segmentation and pricing analysis of 150,000+ UAE vehicle listings. Combines clustering-based market segmentation with interactive Power BI dashboards to surface pricing dynamics, regional distribution patterns, and actionable insights for buyers, sellers, and market entrants.

---

## Key Insights

- Identified 4 distinct market segments via K-Means clustering across price, brand, mileage, and region
- Luxury segment (top 15% by price) concentrated in Dubai Marina and Abu Dhabi
- Japanese brands (Toyota, Nissan, Honda) account for 60%+ of mid-range listings
- SUVs command a 22% price premium over sedans in the same age and mileage bracket

---

## Features

**Data Collection & Preprocessing**
- 150,000+ vehicle listings from UAE classified platforms
- Missing value treatment, outlier handling, and feature normalization
- Categorical encoding for brand, model, region, and body type

**Clustering & Segmentation**
- K-Means clustering with optimal K selection via elbow method and silhouette scores
- Segment profiling: luxury, mid-range daily driver, budget, and commercial
- Regional distribution mapping by emirate

**Power BI Dashboard**
- Pricing heatmap by brand and model year
- Geographic sales distribution across UAE emirates
- Seller demographics and listing activity trends
- Interactive filters for price range, brand, body type, and region

---

## Tech Stack

| Tool | Purpose |
|---|---|
| Python (Pandas, NumPy) | Data preprocessing and analysis |
| Scikit-learn | K-Means clustering |
| Matplotlib / Seaborn | EDA visualizations |
| Power BI | Interactive dashboard |

---

## Project Structure

```
UAE-Vehicle-Market-Analysis/
├── data/
│   └── uae_vehicles.csv
├── notebooks/
│   ├── 01_eda.ipynb
│   ├── 02_preprocessing.ipynb
│   └── 03_clustering.ipynb
├── dashboard/
│   └── uae_vehicle_market.pbix
├── requirements.txt
└── README.md
```

---

## Setup

```bash
git clone https://github.com/mukuldesai/UAE-Vehicle-Market-Analysis
cd UAE-Vehicle-Market-Analysis
pip install -r requirements.txt
jupyter notebook notebooks/01_eda.ipynb
```

---

## Author

**Mukul Desai** — Data Engineer

[![LinkedIn](https://img.shields.io/badge/LinkedIn-mukuldesai-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/mukuldesai)
[![Portfolio](https://img.shields.io/badge/Portfolio-mukuldesai.vercel.app-000000?style=flat&logo=vercel&logoColor=white)](https://mukuldesai.vercel.app)
