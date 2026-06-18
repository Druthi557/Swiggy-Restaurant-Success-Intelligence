# Swiggy-Restaurant-Success-Intelligence
Data analysis of 87,226 Swiggy restaurants across 572 Indian cities to identify market opportunities, success drivers, and expansion strategies

# 🍽️ Swiggy Restaurant Success Intelligence — India 2024

## 📌 Problem Statement
How can a restaurant business use Swiggy data to make 
smarter decisions about where to launch, what cuisine 
to serve, how to price, and whether to invest in offers?

## 📊 Dataset
- Source: Kaggle (rrkcoder — Swiggy Restaurants Dataset)
- Size: 1,40,657 restaurants → 87,226 after cleaning
- Cities: 572 cities across India
- Year: 2024 (scraped data)

## 🛠️ Tools Used
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- SQL (SQLite)
- Power BI (3-page interactive dashboard)

## ❓ Business Questions Answered
1. WHERE should a restaurant launch?
2. WHAT cuisine should it serve?
3. HOW should it price?
4. Should it run OFFERS?
5. Should it go PURE VEG?
6. What does a TOP RATED restaurant look like?

## 🔑 Key Findings
- **Hyderabad** is the strongest launch opportunity — 
  highest engagement (998 avg ratings) but below 
  median quality (3.98 avg rating)
- **Healthy Food** is the biggest cuisine whitespace — 
  4.23 avg rating but only 825 restaurants vs 
  Chinese at 29,677
- **Mid-Range pricing** (Rs200-400) delivers best 
  engagement (639 avg ratings)
- **Moderate offers** (2-3) drive peak engagement 
  at 651 avg ratings — 53% higher than no-offer 
  restaurants
- **Pure Veg** restaurants rate higher in 9 out of 
  10 top cities
- Top 10% restaurants are **92% Mid-Range or Budget** 
  priced — price alone doesn't drive success

## 📈 Dashboard
3-page interactive Power BI dashboard:
- Page 1 — National Overview
- Page 2 — Success Drivers  
- Page 3 — Market Opportunity (includes Market Gap 
  quadrant analysis)

## 📁 Project Structure
Swiggy-Restaurant-Success-Intelligence/

├── notebook/

│   └── Swiggy_Analysis.ipynb

├── sql/

│   └── queries.sql

├── dashboard/

│   └── Swiggy_Dashboard.pbix

├── outputs/

│   └── (charts and visualizations)

└── README.md
## 🚀 How to Run
1. Clone this repository
2. Download dataset from Kaggle (link above)
3. Run `Swiggy_Analysis.ipynb` in Jupyter Notebook
4. Open `Swiggy_Dashboard.pbix` in Power BI Desktop
