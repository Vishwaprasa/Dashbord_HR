
# 📊 Power BI HR Dashboard

<img width="1430" height="802" alt="image" src="https://github.com/user-attachments/assets/e51fea31-c4fc-49b7-8658-6e75cd64090a" />


## 🧠 Purpose

This Power BI report demonstrates an end-to-end **HR analytics solution**, integrating advanced data modeling, dynamic visuals, and performance KPIs to monitor workforce metrics such as salary trends, overtime, and satisfaction levels.

---

## ⚙️ Technical Stack

| Component       | Description                                                                 |
|----------------|-----------------------------------------------------------------------------|
| **Power BI Desktop** | Used for building visuals, designing report layout, and publishing dashboards |
| **DAX (Data Analysis Expressions)** | For calculated columns, KPIs, measures, and time intelligence logic |
| **Power Query (M Language)** | Data transformation, cleansing, and shaping through the Query Editor |
| **Star Schema** | Data modeled in a fact-dimension schema for performance and scalability |
| **Slicer Panels** | Enables user interactivity and filter context across visuals |
| **Bookmarks & Selections** | Enhances navigation and toggling of visual elements |
| **Custom Visuals (optional)** | For advanced visuals such as KPI cards or advanced charts |

---


- **Fact Table**: Contains metrics like salary, overtime, satisfaction, project counts
- **Dimensions**: Role/Position, Department, Date for slicing data

---

## 📐 Report Design Structure

- **KPI Section**: High-level metrics (e.g., Total Bonuses, Leaves Taken)
- **Trends Analysis**: Monthly breakdowns of salary vs hours, overtime vs output
- **Cross-filtered Charts**: Department- and role-level comparisons
- **Correlation Insights**: Satisfaction vs Performance, visually interpreted

---

## 🧩 Optimization Techniques

- Star schema for faster query performance
- Aggregated measures using `SUMX`, `CALCULATE`, `FILTER` for dynamic KPIs
- Minimized visuals on single page to reduce report size and improve load time
- Reusable DAX measures across multiple visuals for consistency

---

## 🧪 Development & Deployment

| Stage        | Tool/Method                    |
|--------------|--------------------------------|
| **Modeling** | Power BI Desktop (Data view, Model view) |
| **ETL**      | Power Query for transformation |
| **Testing**  | Slicer-based validation, DAX testing via DAX Studio |
| **Deployment** | Power BI Service / Workspace for publishing & sharing |

