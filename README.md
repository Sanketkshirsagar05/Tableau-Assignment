# Tableau Assignments

This repository contains a series of Tableau assignments designed to demonstrate various data visualization techniques, dashboard creation, and advanced Tableau features. The assignments range from basic table creation to dynamic, interactive dashboards.

---

## Assignments Overview

### Assignment 1: Sales and Profit Table
- Create a table with:
  - **Rows**: Category and Sub-Category.
  - **Columns**: Region.
  - Metrics: **Total Sales**, **Total Profit**, **Grand Total**, and **Percent of Pane Total**.
- Sort the table by **Sum of Sales** in descending order.
- Ensure formatting matches the example provided.

---

### Assignment 2: Data Combining Techniques & Filtering
- **Dataset**: Netflix Titles.
- Merge tables using **Inner Joins**.
- Identify the actor/actress with the highest number of appearances in **Sports Movies**.
- Provide:
  - Actor/actress's name.
  - Corresponding movie titles they’ve starred in.

---

### Assignment 3: LODs & Histogram
- Create a Tableau histogram to display:
  - **X-axis**: Number of orders.
  - **Y-axis**: Customer count.
- Visualize the count of customers based on their order frequency.

---

### Assignment 4: Sets
- Develop a pie chart that shows:
  - **Top 50 customers** vs. **Other customers** based on the sum of sales.
- Ensure the chart matches the formatting shown in the example image.

---

### Assignment 5: Custom Visuals (KPI Card & Table Calculations)
- Create a KPI card featuring:
  1. **Total Profit** for the current year (last year of the dataset).
  2. **Percentage Growth** from the previous year:
     - Green `▲` for positive growth.
     - Red `▼` for negative growth.
  3. A line chart for **monthly profit trends** in the current year.
- Ensure the design follows the provided guidelines, and use the symbols: `▼` and `▲`.

---

### Assignment 6: Parameters & Groups
1. **Dynamic Bar Chart with Parameter**:
   - Create a parameter named **View by** with the options:
     - **Region**, **Category**, and **Sub-Category**.
   - Display a bar chart of sales based on the selected parameter value.
   - Update the worksheet title dynamically to reflect the parameter's value.
2. **Product Grouping**:
   - Group the following products into categories:
     - Acco, 3M, Samsung, Apple, Xerox.
     - Place remaining products in an "Others" group.
   - Display the **average discount percentage** for each group.

---

### Assignment 7: Advanced Dashboard
- Build a Tableau dashboard using the **Sample Superstore** dataset with the following features:

#### Features
1. **Interactive Layout**:
   - Left panel: Display company logo, interaction controls, and filters for **Year** and **Region**.
   - Right panel: Include 6 dynamic visualizations and 3 KPI cards:
     - **Profit Margin** = Total Profit / Total Sales.
     - **Return Rate** = Quantity Returned / Quantity Ordered.

2. **Dynamic Metrics**:
   - Create a parameter named **Metric** with options:
     - **Sales**, **Profit**, and **# Orders**.
   - Visualizations update dynamically based on the selected metric.
   - Titles and tooltips adjust according to the metric (e.g., "Sales by Category").

3. **Top 5 Products**:
   - Always display the **Top 5 Products** based on the selected metric.

4. **Filter Actions**:
   - Clicking on the **Category Chart** dynamically filters other visualizations and KPI cards.

5. **Clickable Logo**:
   - Clicking the company logo redirects to the published dashboard on Tableau Public.

6. **Show/Hide Filters**:
   - Add buttons to toggle filters for **Year** and **Region**.

7. **Trend & Average Lines**:
   - Include trend lines and average lines where relevant.

8. **Formatting**:
   - Ensure all charts, labels, spacing, and alignment match the provided examples.

---

### Contributions
- Contributions are welcome! If you have suggestions to improve dashboards, visualizations, or the assignment structure, feel free to submit a pull request

### Contact
- For any queries or feedback, reach out to Sanket Kshirsagar.
