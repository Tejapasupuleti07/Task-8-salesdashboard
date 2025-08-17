
# 📊 Sales Dashboard - Task 8 (Data Analyst Internship)

## 📌 Objective
Build a **simple interactive dashboard** that shows sales performance by **Month, Region, and Category** using Power BI or Tableau.

---

## 📂 Dataset
- File: `Superstore_Sales.csv`
- Columns:
  - `Order Date` → Date of order (daily level)
  - `Region` → East, West, Central, South
  - `Category` → Furniture, Office Supplies, Technology
  - `Sales` → Revenue from sales
  - `Profit` → Profit earned
- Size: 100 rows (sample data for practice)

---

## 🛠 Tools Used
- **Power BI** (recommended for easy drag-and-drop visuals)
- OR **Tableau Public**
- (Optional: Python + Pandas for extra data cleaning)

---

## 📈 Dashboard Visuals to Create
1. **Line Chart → Sales over Months**
   - X-axis: Month-Year
   - Y-axis: Sales

2. **Bar Chart → Sales by Region**
   - X-axis: Region
   - Y-axis: Sales

3. **Donut/Pie Chart → Sales by Category**
   - Category shown as segments
   - Sales as values

4. **Slicer/Filter**
   - By `Region` or `Category`

---

## 🔎 Example Insights (from sample data)
- **West Region** recorded the highest sales overall.
- **Technology** category contributed the most revenue share.
- Sales showed a **steady upward trend** month by month.
- **Furniture** sales were strong but with lower profit margins.

---

## ✅ Deliverables
- Dashboard (Screenshot or PDF export)
- 3–4 Insights in a text file or README
- Dataset (`Superstore_Sales.csv`)
- README.md file (this file)

---

## 🚀 Steps to Build
### In Power BI
1. Import CSV → `Get Data → Text/CSV`
2. Change `Order Date` → Date format
3. Create **Month-Year column**:
   ```DAX
   MonthYear = FORMAT('Table'[Order Date], "MMM-YYYY")
   ```
4. Add visuals (Line, Bar, Donut)
5. Add **Slicer** for Region/Category
6. Format → Adjust colors, titles
7. Export → File → Export → PDF

### In Tableau
1. Connect to CSV file
2. Drag `Order Date` → Columns → Convert to Month-Year
3. Drag `Sales` → Rows → Create Line Chart
4. Create Bar (Region vs Sales), Pie/Donut (Category vs Sales)
5. Combine in **Dashboard**
6. Export as Image/PDF

---

## 📌 Submission
- Create a GitHub repo (e.g., `Task-8-Sales-Dashboard`)
- Upload:
  - `Superstore_Sales.csv`
  - `README.md`
  - Dashboard Screenshot / PDF
- Submit repo link using the form.

---

✨ Completed **Task 8: Simple Sales Dashboard**
