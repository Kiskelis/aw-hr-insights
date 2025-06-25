# AW HR Dashboard

<details>
<summary>📂 Project Structure</summary>

- **data/**  
  Raw AdventureWorks HR tables in CSV format.  
- **_aw_hr_dashboard.pbix**  
  The Power BI Desktop file containing all visuals, measures, and model.  
- **Images/**  
  Company logo.  
- **_aw_hr_dashboard_pdf.pdf**  
  A printable guide with screenshots of each report page and explanations of every KPI, chart, and DAX formula.  
- **Dashboard Guide.pptx**  
  Guide to navigate the dashboard.  
  Also available online:  
  https://docs.google.com/presentation/d/1Bk6PmgVXXDUnOPzeFP4VDsApBrsHI0UX/edit?usp=sharing

</details>

---

## 🖥️ Overview

While sharpening my Power BI and data-analysis skills, I chose to build my first end-to-end HR dashboard. Along the way I:

- **Modeled** AdventureWorks HR data into a clean star schema.  
- **Authored** DAX measures for headcount, turnover, net change YTD, average tenure, and more.  
- **Designed** a suite of interactive visuals:  
  - Line chart of employees by year  
  - Back-to-back bars for hires vs. churn  
  - Waterfall of net change YTD  
  - Bubble map by country  
  - Donut chart by gender  
  - Matrix with drill-through and image-tooltips  
- **Implemented** dynamic filtering with slicers and tooltips (hover over a name to see the employee’s photo!).  
- **Learned** best practices in performance, UX, and storytelling with data.

This “AW HR Dashboard” is the product of many late-night experiments, a few head-scratching DAX puzzles, and ultimately a lot of fun exploring HR analytics-from hire dates to hourly rates.

---

## 🎯 Challenges & Growth

Building this dashboard taught me to:

- Tackle **inactive relationships** with `USERELATIONSHIP`.  
- Calculate “**as-of**” metrics (e.g. latest rate per employee) with `LASTNONBLANKVALUE`.  
- Use **row-context** in Power Query to generate dynamic image URLs.  
- Balance aesthetic polish with performance tuning.

I’m proud of the result and excited to keep leveling up as a Power BI specialist and data analyst. 🚀
