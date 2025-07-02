![AIrbnb-1600x533](https://github.com/user-attachments/assets/107a637d-28bc-4141-a756-635c8704d1bd)


## Overview
This project focuses on identifying the **top neighborhoods for Airbnb investment** using ROI modeling. By analyzing listing-level data across New York City, we calculated projected revenue, occupancy, and cost structures to uncover high-performing areas for short-term rental profitability.

The end goal: **Recommend the top 3 neighborhoods for investors** seeking optimal return on investment.

---

## 🎯 Objectives
- Analyze Airbnb listings by neighborhood, room type, and price level
- Calculate estimated monthly revenue based on availability and price
- Model ROI with assumptions on fixed and variable costs
- Rank neighborhoods based on expected profitability

---

## 📊 Dataset
The dataset was sourced from the **Triple Ten Dataset** and includes:
- `Neighborhood Group` (e.g., Manhattan, Brooklyn)
- `Room Type` (Entire home, Private room, etc.)
- `Price`
- `Number of Reviews`
- `Availability_365`
- `Minimum Nights`

## Sample Dataset
*Airbnb-Report ![airbnb_roi](https://github.com/user-attachments/assets/99cdbed0-7eb0-4797-82c3-2d1f0e912348)


---

## 💻 Tools & Technologies
- **Microsoft Excel** – Pivot tables, ROI modeling, data cleaning
- **Google Sheets** – For collaboration and cloud-based visuals
- **Power BI / Tableau** – For dashboard views

---

## 📈 Key Metrics Modeled
- **Estimated Monthly Revenue** = `Price * (Availability_365 / 12)`
- **Fixed Costs** = Mortgage, utilities, cleaning ($ estimates)
- **Variable Costs** = % of revenue for management fees, turnover, etc.
- **ROI (%)** = `(Estimated Profit / Total Investment) * 100`

---

## 🔍 Findings
- **Brooklyn** and **Queens** had strong returns for mid-priced private rooms
- **Entire homes** in **Manhattan** had high revenue but lower ROI due to higher costs
- Top 3 neighborhoods for investment (based on ROI):  
  1. Bushwick (Brooklyn)  
  2. Astoria (Queens)  
  3. Harlem (Manhattan)

## 📌 Strategic Recommendation

To optimize Airbnb investment performance in NYC:

- 📦 **Target mid-range properties in outer boroughs** (Brooklyn, Queens) with low fixed costs and high occupancy potential.
- 📈 **Avoid over-leveraging in Manhattan** despite high nightly rates — ROI is diluted by elevated mortgages and taxes.
- 💬 **Focus on private rooms and shared listings** in gentrifying areas like Bushwick and Astoria, which offer high turnover and scalable margins.
- 📊 Use dynamic pricing strategies based on seasonality and availability to maximize occupancy rates.

These strategies help investors align short-term rental goals with sustainable profit margins.
