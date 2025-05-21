# Call Center Performance Dashboard – OptiConnect Solutions

A Power BI project to analyze and optimize call center performance for **OptiConnect Solutions**, a leading customer service provider based in Technoville. This dashboard helps uncover key insights around agent performance, customer satisfaction, call volume trends, and resolution efficiency.

---

## Project Objective

To build an interactive dashboard that enables call center management to:
- Track call volume, answer/resolution rates, and customer satisfaction.
- Identify top-performing agents and departments.
- Analyze the relationship between service metrics and satisfaction.
- Discover improvement areas for better operational efficiency.

---

## Dataset Overview

The dataset contains call-level records with the following columns:

| Column Name           | Description                                |
|-----------------------|--------------------------------------------|
| `ID`                  | Unique Call ID                             |
| `Date`                | Timestamp of the call (e.g., 31-01-2016 17:34) |
| `Agent`               | Name of the call center agent              |
| `Department`          | Product department (e.g., Fridge, Mobile)  |
| `Answered` (Y/N)      | Whether the call was answered              |
| `Resolved` (Y/N)      | Whether the issue was resolved             |
| `Speed of Answer`     | Time taken to answer the call (in seconds) |
| `AvgTalkDuration`     | Average call duration (hh:mm:ss)           |
| `Satisfaction Rating` | Customer rating from 1 (Low) to 5 (High)   |

---

## Dashboard Structure

### 🔹 Sheet 1: **Call Center Performance Overview**
Visualizes overall performance KPIs and call trends.

- **KPI Cards**:
  - Total Calls
  - Answer Rate %
  - Resolved Rate %
  - Avg. Satisfaction

- **Donut Charts**:
  - Answered vs. Missed Calls
  - Resolved vs. Not Resolved

- **Line Chart**:
  - Calls Answered Over Time (Date-based trend)

- **Clustered Bar Chart**:
  - Avg. Speed of Answer by Department

- **Slicers**:
  - Agent
  - Department

---

### 🔹 Sheet 2: **Agent Performance & Satisfaction Analysis**
Focuses on individual agent metrics and customer satisfaction factors.

- **Matrix Table**:
  - Agent-wise Metrics: Calls Handled, Answer Rate %, Resolved %, Avg. Satisfaction

- **Bar Chart**:
  - Top 10 Agents by Average Satisfaction

- **Scatter Plots**:
  - Speed of Answer vs. Satisfaction
  - Avg Talk Duration vs. Satisfaction

- **Matrix**:
  - Department vs. Avg. Satisfaction

- **Line Chart**:
  - Satisfaction Rating Trend Over Time

---

## Tools Used

- **Power BI Desktop**
- **DAX (Data Analysis Expressions)**
- **Power Query** for date-time formatting and column transformations

---

## Key Insights Uncovered

- Relationship between fast responses and higher satisfaction.
- Department-wise performance variations.
- Top-performing agents by resolution efficiency and customer feedback.
- Time-based trends in satisfaction and call handling.

---

