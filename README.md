# 🏡 Rental Pricing Advisor – Capstone Project
Capstone project - SmartRentalReports.com


**Live App:** [https://smartrentalreports.com](https://smartrentalreports.com)  
**n8n Report Example:** [View HTML Report](https://smartrentalreports.com/report.html?zip=33101&median_price=2400)

---

## 🎯 Overview

The Rental Pricing Advisor is a data-driven web application that helps property managers and real estate investors in **Miami-Dade County** determine fair and competitive rental prices for their residential units.

Built using real ZORI data from Zillow, the app calculates and displays **recommended rent**, **min/max rent ranges**, and **market trends** — all by ZIP Code.

---

## 📊 Key Features

- ✅ **ZIP Code Selector** for targeted rent estimates
- ✅ **Median, Min, and Max Rent** insights based on real market data
- ✅ **Clean HTML report** dynamically generated via **n8n**
- ✅ **Responsive UI**, mobile-friendly and fast-loading
- 🛠️ Placeholder UI elements for future filters (e.g., bedrooms, property type)
- 📈 Panel with market summary: growth, occupancy rate, time on market

---

## 🧠 Tech Stack

| Layer         | Tech                       |
|---------------|----------------------------|
| Frontend      | React (https://github.com/your-username/rental-pricing-advisor-frontend), HTML, CSS |
| Backend Logic | n8n (no-code workflow automation) |
| Hosting       | Netlify (frontend), n8n Cloud (report engine) |
| Data Source   | Zillow ZORI Dataset (CSV) |

---

## 📁 Dataset Details

- **Filename:** `miami_dade_zori_long_2020_2025.csv`
- **Source:** Zillow Observed Rent Index (ZORI)
- **Columns used:** `RegionName`, `Year`, `ZORI_Rent`
- **Filter:** Most recent year for each ZIP code

---

## 🚀 Future Enhancements

- 📊 Add dynamic trend charting (historical rent over time)
- 🛒 CSV or PDF report export
- 🛏️ Enable filtering by bedroom count and property type
- 🌐 Compare short-term rental prices (Airbnb integration)

---

## 👩‍💻 Authors

**Marilian Lopez, Samanta Castro, Jomar Arroyo**  
Capstone Project – Bachelor of Science in Data Analytics  
Miami Dade College | 2025

---

## 📷 Screenshots

> _(Include screenshots of the homepage, ZIP selector, and sample report if possible)_ Included in the Power POint

---

**Live App:** [https://smartrentalreports.com](https://smartrentalreports.com)  
**GitHub Repo:** [https://github.com/your-username/rental-pricing-advisor-frontend](https://github.com/your-username/rental-pricing-advisor-frontend)  
**n8n Report Example:** [Generate Report](https://smartrentalreports.com/report.html?zip=33101&median_price=2400)

---

## 📜 License

This project is for academic purposes only.
