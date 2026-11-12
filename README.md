# SWYNEX – Student Performance Analytics Dashboard

### Interactive Data Analytics Dashboard | Power BI | SWYNEX Internship – Task 3

---

##  Project Overview

The **Student Performance Analytics Dashboard** is an interactive business intelligence project developed using Microsoft Power BI as part of the SWYNEX Internship – Task 3.

The primary objective of this project is to analyze student academic performance and identify the factors that may influence examination results.

The dashboard transforms cleaned student data into meaningful visual insights through interactive charts, KPI cards, and dynamic filters.

It enables users to explore student performance across different categories, compare academic indicators, and understand patterns related to study habits, attendance, motivation, parental involvement, and sleep duration.

---

## Project Objectives

- Analyze overall student academic performance.
- Identify the distribution of students across performance categories.
- Evaluate the relationship between study hours and examination scores.
- Compare academic performance across school types and genders.
- Analyze the influence of motivation and parental involvement.
- Explore the relationship between sleep duration and average examination scores.
- Build an interactive dashboard for effective data exploration and decision-making.

---

##  Dataset Information

The project uses a cleaned student performance dataset.

| Dataset Attribute | Details |
|---|---|
| Dataset Name | cleaned_student_data.csv |
| Total Records | 6,607 |
| Total Columns | 20 |
| Data Format | CSV |
| Data Preparation | Power Query |
| Visualization Tool | Microsoft Power BI |

The dataset contains student-related academic and behavioral attributes used to explore performance patterns.

---

##  Tools & Technologies

| Tool / Technology | Purpose |
|---|---|
| Microsoft Power BI Desktop | Dashboard development |
| Power Query | Data cleaning and preparation |
| DAX | Calculated measures and KPIs |
| CSV | Dataset storage and input |
| Data Visualization | Analytical presentation |

---

## Dashboard Overview

The dashboard is designed with a professional **Dark Navy and Teal** color theme to provide a clean and visually consistent analytical experience.

### 1. Key Performance Indicators (KPIs)

The dashboard includes six KPI cards:

1. **Total Students** – Displays the total number of students in the current dashboard context.
2. **Average Study Hours** – Shows the average number of study hours.
3. **Average Exam Score** – Displays the overall average examination score.
4. **Average Attendance** – Represents the average student attendance.
5. **High Performers Count** – Shows the number of students classified as high performers.
6. **Median Exam Score** – Displays the median examination score.

### 2. Data Visualizations

The dashboard contains eight interactive visualizations.

| No. | Visualization | Analytical Purpose |
|---|---|---|
| 1 | Student Performance Distribution – Donut Chart | Shows the distribution of performance categories. |
| 2 | Student Count by Performance Category – Column Chart | Compares student counts across performance levels. |
| 3 | Average Exam Score by School Type – Bar Chart | Compares academic scores across school types. |
| 4 | Average Attendance by Performance Category – Bar Chart | Examines attendance patterns across performance levels. |
| 5 | Study Hours vs Exam Score by Gender – Scatter Chart | Explores the relationship between study time and exam scores by gender. |
| 6 | Average Exam Score by Motivation Level & Gender – Stacked Column Chart | Compares academic scores across motivation levels and genders. |
| 7 | Student Distribution by Parental Involvement – Treemap | Visualizes student distribution by parental involvement. |
| 8 | Average Exam Score by Sleep Hours – Line Chart | Explores score patterns across sleep-hour groups. |

### 3. Interactive Slicers

Five slicers are implemented to allow dynamic filtering.

- Gender
- School Type
- Motivation Level
- Parental Involvement
- Internet Access

Users can combine multiple slicers to explore specific student segments and analyze changes across KPI cards and visualizations.

### 4. Reset Filters Functionality

A dedicated **Reset Filters** button is implemented using Power BI Bookmarks.

This functionality allows users to:

- Clear applied slicer selections.
- Restore the default dashboard view.
- Return to the original KPI and chart context.
- Improve the overall dashboard navigation experience.

---

##  Dashboard Design

The dashboard follows a consistent Dark Navy and Teal visual theme.

| Design Element | Color Code |
|---|---|
| Background | `#0B132B` |
| Teal | `#14B8A6` |
| Blue | `#3B82F6` |
| White | `#FFFFFF` |

The design focuses on readability, consistent visual hierarchy, clear KPI presentation, and interactive exploration.

---

##  Data Preparation & Development Process

The project was developed through the following workflow:

**Step 1 – Data Preparation**
- Imported the cleaned CSV dataset into Power BI.
- Used Power Query for data preparation.
- Created an Index column for record identification.

**Step 2 – Data Analysis**
- Developed DAX measures for analytical calculations.
- Created KPI measures for student performance indicators.
- Prepared measures for average and median score analysis.

**Step 3 – Dashboard Development**
- Designed and formatted six KPI cards.
- Created eight data visualizations.
- Implemented five interactive slicers.

**Step 4 – Interactivity**
- Configured slicer interactions.
- Created a Default View bookmark.
- Implemented the Reset Filters button.
- Tested the dashboard's default and filtered states.

**Step 5 – Finalization**
- Applied a consistent dashboard theme.
- Refined visual alignment and formatting.
- Saved the final Power BI project.

---

##  Project Structure

```text
SWYNEX-Student-Performance-Analytics/
│
├── Dashboard/
│   └── SWYNEX_Student_Performance_Analytics_Final.pbix
│
├── Dataset/
│   └── cleaned_student_data.csv
│
├── Screenshots/
│   └── Dashboard.png
│
└── README.md
```

---

##  Key Analytical Questions

This dashboard helps explore questions such as:

1. How are students distributed across different performance categories?
2. How do average examination scores differ between school types?
3. What attendance patterns can be observed across performance categories?
4. How do study hours relate to examination scores?
5. How do motivation levels and gender relate to average exam scores?
6. How is student distribution associated with parental involvement categories?
7. How do average examination scores vary across sleep-hour groups?
8. How do academic indicators change when different student segments are selected?

---

##  Skills Demonstrated

- Data Cleaning & Preparation
- Power Query
- DAX Calculations
- KPI Development
- Data Modeling Fundamentals
- Interactive Dashboard Development
- Data Visualization
- Analytical Thinking
- Business Intelligence Reporting
- Dashboard Design & Formatting

---

##  Learning Outcomes

Through this project, I gained practical experience in:

- Transforming datasets into analytical reports.
- Developing calculated measures using DAX.
- Designing interactive Power BI dashboards.
- Using slicers and bookmarks to improve user experience.
- Selecting suitable visualizations for different analytical requirements.
- Presenting data insights through a structured dashboard.

---

##  Future Enhancements

Potential improvements for future versions include:

- Adding advanced performance trend analysis.
- Developing drill-through pages for detailed student analysis.
- Implementing additional comparative KPIs.
- Creating more detailed student segmentation.
- Exploring predictive analytics for academic performance.

---

##  Author

**Developed as part of the SWYNEX Internship – Task 3.**

**Project:** Student Performance Analytics Dashboard  
**Domain:** Data Analytics / Business Intelligence  
**Primary Tool:** Microsoft Power BI Desktop

---

 If you find this project interesting, feel free to explore the dashboard and its interactive analytical features.

