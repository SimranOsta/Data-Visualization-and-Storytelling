# Data Analyst Internship - Task 2  
**Data Visualization and Storytelling using Tableau**

## 📌 Objective
Create visualizations that convey a compelling story using the provided dataset (`List of Orders.csv`).  
Focus on business insights, not just visuals.

---

## 📂 Dataset
- **File Used:** `List of Orders.csv`
- **Fields:**
  - Order ID
  - Order Date
  - Customer Name
  - State
  - City
- **Time Period:** April 2018 – February 2019
- **Size:** ~1,000+ records

---

## 🛠️ Tools
- **Tableau Public** (free version)
- GitHub for submission

---

## 📊 Steps Followed

1. **Install & Open Tableau**  
   - Downloaded Tableau Public and created a new workbook.

2. **Connect to Dataset**  
   - Imported `List of Orders.csv` into Tableau.

3. **Explore the Data**  
   - Verified data types:
     - `Order Date` → Date field  
     - `State` and `City` → Geographic fields  
   - Removed blank rows at the bottom.

4. **Create Charts**  
   - **Orders Over Time** → Line chart using `YEAR(Order Date)` vs `COUNT(Order ID)`  
   - **Orders by State** → Bar chart showing order volume per state  
   - **Orders by City** → Bar chart showing order volume per city  
   - **Geographic Map** → Map visualization of orders across India

5. **Choose the Right Chart**  
   - Line chart for trends  
   - Bar chart for comparisons  
   - Map for geographic distribution  
   - Avoided clutter and unnecessary pie charts

6. **Add Filters & Highlights**  
   - Added filters for `Order Date` (monthly/yearly)  
   - Added filters for `State` and `City`  
   - Used color highlights to emphasize top-performing states

7. **Build Dashboard**  
   - Combined multiple charts into a single dashboard  
   - Added interactive filters for date and state  
   - Organized layout: Overview → Drill-down → Insights

8. **Tell the Story**  
   - Orders grew steadily across months  
   - Maharashtra and Madhya Pradesh had the highest order volumes  
   - Cities like Mumbai, Indore, and Pune were top contributors  
   - Geographic spread shows strong presence across India

9. **Export & Submit**  
   - Exported dashboard screenshots as PDF  
   - Uploaded dataset, screenshots, and README.md to GitHub

---

## 📈 Key Insights
- **Maharashtra** consistently had the highest number of orders.  
- **Indore and Mumbai** were major order hubs.  
- Orders were spread across almost all states, showing wide customer reach.  
- Seasonal spikes in orders appeared around mid-year (June–July).

---

## 📌 Deliverables
- Tableau workbook (`.twb` or `.twbx`)  
- Dashboard screenshots / PDF export  
- Dataset (`List of Orders.csv`)  
- README.md (this file)

---

## ✅ Submission Guidelines Followed
- Self-research and debugging done independently  
- No paid tools used  
- GitHub repository created with all files included  

---

## 🚀 Outcome
Mastered the art of **visual storytelling with charts and dashboards in Tableau**, turning raw order data into meaningful business insights.
