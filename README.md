# Bharat Insights – Income, Occupation & Literacy Dashboard

An interactive **Power BI** dashboard analyzing income levels, occupation trends, and literacy rates across Indian states and union territories. The report combines multiple visual pages with a dark, futuristic theme to deliver clear, data-driven insights.

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 📊 Overview

This dashboard explores demographic and socio-economic data across India, covering:

- **Income** — average and total income by state, occupation, and gender
- **Occupation** — distribution of persons across different professions
- **Literacy Rate** — state-wise literacy trends, urban/rural split, and year-wise survey history

---

## 🗂️ Dashboard Pages

| Page | Description |
|------|-------------|
|Page 1 -- **Sum of Annual Income by State** | KPI cards and a state-wise bar chart showing total income, with color gradient highlighting top/bottom performing states |
|Page 2-- **Average of Annual Income by Occupation** | Ranks occupations by average income (highest to lowest) alongside an overall average income card |
|Page 3-- **Count of Persons by Occupation** | Line/area chart showing the number of people engaged in each occupation, plus a "Top Occupation" KPI |
|Page 4-- **Literacy Rate by States and Area** | State-wise literacy rate bar chart (gradient colored), a year-wise literacy survey treemap (2017–2023), and a pie chart splitting literacy by urban/rural/rural+urban area 
|Page 5-- **Male vs Female Avg Income** | Compares average male and female income overall and broken down by state |

---

## 📈 Key Visuals Used

- Clustered & stacked bar charts
- Line and area charts
- Pie chart
- Treemap
- KPI / Card visuals
- Gradient-based conditional formatting for data-driven color coding

---

## 🧾 Data Fields

The report is built on the following core fields:

- `State`, `Country`
- `Income`, `Male Avg Income`, `Female Avg Income`
- `Occupation`, `Top Occupation`
- `Literacy rate`, `Type of area`, `YearCode`
- `Gender`, `Maritial Status`
- `Education Till`, `Medium of Study`

---

## 🛠️ Tools & Technologies

- **Power BI Desktop** — report building and data modeling
- **DAX** — calculated measures (sums, averages, counts)
- **Conditional Formatting** — gradient color scales for visual emphasis

---

## 🚀 How to Use

1. Clone or download this repository
2. Open **`Bharat Insights Income, Occupation & Literacy Dashboard.pbit`** in **Power BI Desktop**
3. When prompted, connect it to your dataset (or use the sample data provided, if included)
4. Explore the report pages using the navigation tabs at the bottom

> **Note:** This is a `.pbit` (Power BI Template) file. On first open, Power BI will ask you to load/refresh data before rendering the visuals.

---

## 📌 Insights Highlighted

- States like **Mizoram, Lakshadweep, and Nagaland** show the highest literacy rates
- **Business owners, doctors, and lawyers** report the highest average incomes among occupations
- Literacy is fairly evenly split across **urban, rural, and combined rural+urban** areas
- A visible **income gap exists between average male and female earnings** across most states

---

## 📄 License

This project is open for educational and portfolio use. Feel free to fork and adapt it for your own data storytelling projects.

---

## 🙋‍♂️ Author

Created as part of a data visualization/analytics portfolio project using Power BI.
