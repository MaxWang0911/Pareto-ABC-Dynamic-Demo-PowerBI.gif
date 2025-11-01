# Dynamic Pareto ABC Analysis （Power BI）

An interactive Power BI dashboard that performs **dynamic Pareto ABC classification** based on KPI metrics (Sales Amount / Sales Profit / Sales Quantity).  
Users can dynamically switch **metrics**, **dimensions**, **ABC threshold parameters**, and **TOP N filtering** — all without modifying DAX or visuals.

---

##  Features

| Feature | Description |
|---------|-------------|
| ✅ Dynamic ABC Classification | Auto assigns items into A/B/C based on cumulative KPI percentage. |
| ✅ Dimension Switching | User can switch ABC dimension (Customer State / Product Category / Salesperson). |
| ✅ KPI Selection | Toggle between Sales Amount / Sales Profit / Sales Quantity. |
| ✅ Parameter Controls | Users can adjust ABC % thresholds and TOP N display. |
| ✅ Pareto Chart | Bars + cumulative % line (Pareto) in one visual. |
| ✅ ABC Donut Charts | Shows group distribution by count & by contribution. |
| ✅ Full interaction | Slicer filtering affects all charts dynamically. |

---

## 🔧 Tech Highlights

###  Advanced DAX used:
- `SWITCH()` + `SELECTEDVALUE()` for dynamic metric switching  
- `TREATAS()` + `KEEPFILTERS()` for mapping disconnected dimension table  
- ABC Classification logic based on cumulative KPI

> No hardcoding. No static grouping.


 If you like this repository, please give it a star!⭐

---
---
 
How to Use

Open Max_Dynamic Pareto ABC Analysis.pbix in Power BI Desktop

Select Metric (Sales Amount / Profit / Quantity)

Select Dimension (Product Category / Customer State / Salesperson)

Adjust ABC Threshold % and TOP N

Charts will update dynamically

---
---

Roadmap / Future Improvements

 Add export report page to PDF template

 Add multi-measure comparison mode

 Publish as Power BI App

🧑‍💻 Author / Contact 
Max Wang
Sydney, Australia
