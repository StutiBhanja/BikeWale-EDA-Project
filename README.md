# 🏍️ BikeWale — Web Scraping & EDA Project

![Python](https://img.shields.io/badge/Python-3.x-blue) ![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup-4-green) ![Pandas](https://img.shields.io/badge/Pandas-EDA-yellow) ![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

## 📋 Problem Statement
Analyze the factors affecting bike prices in India — brand, engine displacement, mileage, and weight — using real data scraped from [BikeWale.com](https://www.bikewale.com).

---

## 📦 Dataset
| Detail | Info |
|--------|------|
| Source | BikeWale.com (Web Scraped) |
| Records | 449 bikes |
| Features | 7 columns |
| Method | requests + BeautifulSoup |

**Columns:** `Brand`, `Model`, `Price_INR`, `Engine_CC`, `Mileage_KMPL`, `Weight_KG`, `Fuel_Tank_L`

---

## 🔧 Tools & Libraries
- **Scraping** — requests, BeautifulSoup, re, json
- **Analysis** — Pandas, NumPy
- **Visualization** — Matplotlib, Seaborn

---

## 📊 Key Findings
- 💰 Price is right-skewed — 33% of bikes are Budget segment (< ₹80K)
- ⚙️ Engine CC is the strongest price predictor (r = 0.87)
- 🏷️ Hero, Bajaj, TVS dominate budget; BMW, Ducati, Kawasaki lead luxury
- ⚡ EV bikes (Ather, Ola) are competitively priced against 150–200cc petrol bikes
- 📉 Mileage has an inverse relation with price (r = −0.54)

---

## 📁 Files
| File | Description |
|------|-------------|
| `BikeWale_EDA_Project.ipynb` | Main notebook — scraping, cleaning & EDA |
| `bikewale_data.csv` | Scraped dataset |
---

## 🙋‍♀️ Author
**Stuti Bhanja** — Aspiring Data Scientist
🔗 [GitHub](https://github.com/StutiBhanja)
