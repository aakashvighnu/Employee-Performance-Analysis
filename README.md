# 📊 Employee Performance Analysis | Excel & Power BI

## 📌 Project Overview

The Employee Performance Analysis project is an HR analytics mini project designed to evaluate employee performance, workforce distribution, performance reviews, talent potential, promotions, and goal achievement.

This project uses Microsoft Excel for data cleaning, preprocessing, and exploratory data analysis, and Microsoft Power BI for data modelling, interactive dashboard creation, and business intelligence reporting.

The primary objective is to transform raw HR data into meaningful insights that support data-driven decision-making, employee development, and organizational performance improvement.

## 🎯 Project Objectives

- Analyze employee distribution across departments and job levels.
- Evaluate employee performance ratings and review completion.
- Identify high-performing employees and talent development opportunities.
- Analyze promotion records and promotion rates.
- Measure employee goal achievement and success rates.
- Compare employee self-assessments with manager evaluations.
- Develop interactive dashboards using Power BI.

## 🛠️ Tools and Technologies Used

- **Microsoft Excel** – Data cleaning, preprocessing, formulas, Pivot Tables, Pivot Charts, and dashboard creation.
- **Microsoft Power BI** – Data modelling, interactive dashboards, and visualization.
- **Power Query** – Data transformation and validation.
- **DAX (Data Analysis Expressions)** – Calculated columns, measures, and KPI calculations.
- **GitHub** – Project documentation and version control.

## 📂 Dataset Description

The project consists of four interconnected datasets.

| Dataset | Number of Records | Description |
|---|---:|---|
| Employees | 1,200 | Employee demographics, departments, salaries, and employment details |
| Performance Reviews | 5,064 | Performance ratings, review status, potential ratings, and promotions |
| Performance Goals | 27,698 | Employee goals, achievement percentages, and goal status |
| Review Cycles | 5 | Performance review periods and cycle information |
| **Total** | **33,967** | Combined records across all four datasets |

## 🧹 Data Cleaning and Preprocessing

The following preprocessing techniques were performed using Microsoft Excel:

- Duplicate record verification.
- Missing value identification and treatment.
- Standardization of categorical values.
- Data type and format validation.
- Creation of calculated columns.
- Cleaning of performance ratings and rating labels.
- Handling missing potential ratings and nine-box classifications.
- Standardization of promotion status.
- Integration of department and review cycle information using XLOOKUP.
- Creation of Pivot Tables and Pivot Charts.
- Development of an Excel dashboard with key performance indicators.
- Documentation of preprocessing activities in a cleaning log.

## 🔗 Data Modelling

A data model was created in Power BI using one-to-many relationships between the four datasets.

- Employees → Performance Reviews
- Employees → Performance Goals
- Review Cycles → Performance Reviews
- Review Cycles → Performance Goals

The model uses employee ID and cycle ID as relationship keys, enabling consistent filtering and cross-table analysis.

## 📈 Power BI Dashboards

The Power BI report consists of four interactive dashboard pages.

### 1. Employee Overview Dashboard

Provides an overview of workforce demographics and organizational structure.

**Key visualizations:**

- Total employees
- Total departments
- Average annual salary
- Average employee tenure
- Department-wise employee distribution
- Gender distribution
- Job-level distribution
- Department-wise salary analysis
- Employment type distribution
- Employee tenure analysis

### 2. Performance Analysis Dashboard

Evaluates employee performance, review completion, and promotion trends.

**Key visualizations:**

- Total performance reviews
- Completed reviews
- Review completion rate
- Average performance rating
- Total promotions
- Promotion rate
- Performance rating distribution
- Department-wise performance analysis
- Review cycle trends
- Self-assessment vs manager assessment
- Promotion analysis

### 3. Nine-Box Talent Matrix Dashboard

Analyzes talent distribution based on employee performance and potential.

The matrix categorizes completed performance reviews into three analytical groups:

- 🟢 Strong Talent
- 🟡 Development
- 🔴 Needs Attention

Conditional formatting and DAX measures are used to create a dynamic, colour-coded talent matrix.

### 4. Goal Achievement Dashboard

Analyzes employee goal completion and organizational target achievement.

**Key visualizations:**

- Total performance goals
- Average goal achievement
- Achieved goals
- Goal success rate
- Goal status distribution
- Goal achievement gauge
- Department-wise goal achievement
- Goal category analysis
- Goal achievement trends
- Stretch vs regular goal analysis

## 📊 Key Performance Indicators

| KPI | Result |
|---|---:|
| Total Employees | 1,200 |
| Total Departments | 11 |
| Average Annual Salary | $92,140 |
| Total Performance Reviews | 5,064 |
| Completed Reviews | 3,974 |
| Pending Reviews | 1,090 |
| Review Completion Rate | 78.48% |
| Average Performance Rating | 3.20 / 5 |
| Total Promotion Records | 86 |
| Promotion Rate | 2.16% |
| Total Performance Goals | 27,698 |
| Average Goal Achievement | 91.27% |
| Achieved Goals | 9,012 |
| Goal Success Rate | 32.54% |

## 👥 Talent Classification Analysis

| Talent Classification | Completed Reviews | Percentage |
|---|---:|---:|
| Strong Talent | 1,930 | 48.57% |
| Development | 1,168 | 29.39% |
| Needs Attention | 876 | 22.04% |
| **Total** | **3,974** | **100%** |

## 💡 Key Insights

- Operations has the largest employee population among the departments.
- Approximately 78.48% of performance reviews have been completed.
- The average employee performance rating is 3.20 out of 5.
- Approximately 48.57% of completed reviews fall under the Strong Talent classification.
- Around 22.04% of completed reviews indicate areas requiring additional attention.
- The average goal achievement rate is 91.27%.
- Partially achieved goals represent the largest goal status category.
- Despite a high average achievement percentage, only 32.54% of goals are classified as fully achieved, indicating opportunities for improvement in goal completion.

## 🚀 Recommendations

- Provide targeted training and development programmes.
- Improve performance review completion through regular monitoring.
- Establish mentorship programmes for employees with development potential.
- Recognize and reward high-performing employees.
- Review goal-setting strategies to improve full goal completion.
- Use performance dashboards to support continuous HR monitoring and decision-making.

## ⚙️ Dashboard Features

- Interactive slicers and filters
- Dynamic KPI cards
- DAX measures and calculated columns
- Conditional formatting
- Nine-box talent matrix
- Cross-table filtering
- Department-wise analysis
- Review cycle analysis
- Consistent purple-themed dashboard design
- Multiple interactive report pages

## 📁 Repository Contents

| File | Description |
|---|---|
| AAKASH VIGHNU MINI PROJECT.xlsx | Cleaned dataset, Pivot Tables, KPI calculations, and Excel dashboard |
| AAKASH VIGHNU MINI PROJECT.pbix | Interactive Power BI report |
| AAKASH VIGHNU MINI PROJECT.pdf | Exported Power BI dashboard report |
| README.md | Project documentation |

## 🔍 How to Use This Project

1. Download or clone this repository.
2. Open the Excel workbook using Microsoft Excel.
3. Explore the cleaned datasets, Pivot Tables, and Excel dashboard.
4. Open the PBIX file using Power BI Desktop.
5. Explore the four interactive dashboard pages.
6. Use slicers to filter results by department, review cycle, job level, and other available categories.

## 📝 Analytical Limitations

- Talent classifications represent completed performance review records rather than unique employees.
- Cleaned potential ratings include imputed values.
- Original final ratings and completed reviews are used for the main performance rating analysis.
- Average goal achievement and goal success rate represent different performance metrics.

## 🎓 Learning Outcomes

Through this project, I gained practical experience in:

- Data cleaning and preprocessing
- Exploratory data analysis
- Advanced Excel formulas
- Pivot Tables and Pivot Charts
- Power BI data modelling
- DAX measures and calculated columns
- Interactive dashboard development
- HR analytics and business intelligence
- Data storytelling and insight generation

## 📌 Conclusion

This project demonstrates how Excel and Power BI can be used together to transform raw employee performance data into actionable business insights.

The dashboards provide a comprehensive view of workforce distribution, employee performance, talent potential, promotions, and goal achievement, helping organizations identify strengths, development opportunities, and areas requiring improvement.

## 👨‍💻 Author

**Aakash Vighnu**

Data Analytics Mini Project

**Skills:** Microsoft Excel | Power BI | Power Query | DAX | Data Visualization | HR Analytics

---

⭐ If you find this project useful, consider giving this repository a star!
