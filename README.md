# ☕ Coffee Shop Sales Dashboard — Excel

An interactive sales dashboard built in Microsoft Excel analysing 
214,500+ transactions across 3 New York coffee shop locations 
(Astoria, Hell's Kitchen, Lower Manhattan) from January to June 2023.

> 🎨 Dashboard aesthetic inspired by Pinterest minimal design.
> Built entirely in Excel on Mac (no Power Pivot available) in ~3 hours.
> This is my first end-to-end Excel dashboard project.

---

## 📊 Dashboard Features

- Dynamic **Store Location slicer** — filters entire dashboard by location
- **Timeline filter** — slice revenue and orders by specific months
- KPI cards — Total Revenue, Total Orders, AOV, Store-wise metrics
- Donut charts, bar charts, and pivot-based visuals on a single view

---

## 🛠️ Excel Techniques Used

| Technique | Application |
|---|---|
| `SUMIF` | Revenue by product category, store-wise revenue totals |
| `COUNTIF` | Order count by product type and category |
| `IF` | Weekday vs Weekend classification, conditional labelling |
| `AVERAGE` | Average Order Value (AOV) calculation |
| `INDEX + MATCH` | Dynamic Top 3 Products and Top 3 Categories |
| PivotTables | All chart data — category, monthly, store, size breakdowns |
| PivotCharts | Bar charts and donut charts linked to slicers |
| Timeline Slicer | Interactive month-based filtering |
| Conditional Formatting | Data sheet highlights for quick pattern recognition |

---

## ❓ Business Questions & Answers

**1. Which product category drives the most sales?**
Coffee leads with 20,025 orders, followed by Tea (16,260) and Bakery (7,289).
Coffee + Tea together account for ~72% of all transactions.

**2. What is the monthly revenue trend?**
Revenue grew consistently from ₹27,314 in January to ₹55,083 in June —
a 2x growth over 6 months. February was the only dip (-9% MoM),
likely due to fewer calendar days and no promotional activity.

**3. Which store performs best?**
Store 8 (Lower Manhattan) generates the highest revenue at ₹405,880 —
nearly equal to Astoria and Hell's Kitchen combined.

**4. What size do customers prefer?**
"Not Defined" and Regular sizes lead at 33% and 29% respectively.
Large accounts for 29%. Small is least preferred at 9% —
suggesting customers lean toward standard or larger portions.

**5. Who are the top 3 products?**
Barista Espresso, Gourmet Brewed Coffee, and Brewed Chai Tea
consistently rank as the highest ordered items across all locations.

**6. When is the business busiest?**
June recorded the highest monthly orders at 16,965, with May close behind at 16,175 — suggesting a strong
late-spring seasonal trend worth planning inventory around.

**7. What is the Average Order Value (AOV)?**
₹3.21 per transaction across all stores.
Lower Manhattan edges slightly higher, indicating a
marginally more premium customer base in that location.

---

## 💡 Key Business Insights

- **Coffee is king** — prioritise stock and promotions around coffee products
- **Feb needs attention** — a targeted campaign could recover the seasonal dip
- **Lower Manhattan outperforms** — study its product mix and replicate in other stores
- **Small size is unpopular** — consider removing or replacing with a new size offering

---

## 📁 Files
- `Coffee_Shop_Sales.xlsx` — Raw data + Data Analytics + 
   Time Analytics + Dashboard + Report sheets

---

## 🛠️ Tools
Microsoft Excel (Mac) · PivotTables · PivotCharts · Slicers · 
Timeline Filter · SUMIF · COUNTIF · IF · INDEX MATCH

---

*Dashboard design inspired by minimal Pinterest aesthetics.
Built by Prachi Sharma | April 2026*
