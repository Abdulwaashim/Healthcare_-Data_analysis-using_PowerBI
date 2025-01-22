# Non-Communicable Diseases (NCDs) Analysis and Healthcare Insights

This project analyzes Non-Communicable Diseases (NCDs) data to uncover trends, visualize health metrics, and gain actionable insights. The dataset focuses on key metrics such as patient demographics, blood sugar levels, cholesterol levels, and hospital visits.

## Project Overview
Non-communicable diseases (NCDs) such as cardiovascular diseases, diabetes, and chronic respiratory conditions are among the leading causes of death worldwide. This analysis explores:

- Trends in patient demographics (age, gender) for specific diseases.
- Blood sugar and cholesterol levels by disease type.
- Frequency of hospital visits over time.

## Dataset Details
A mock dataset was created for this project, containing the following columns:

- **Patient_ID**: Unique ID for each patient.
- **Age**: Patient's age.
- **Gender**: Male/Female/Other.
- **Disease_Type**: Types of diseases (e.g., Diabetes, CVD).
- **Hospital_Visit_Date**: Date of hospital visit.
- **Blood_Sugar_Level**: Numeric value for blood sugar level.
- **Cholesterol_Level**: Numeric value for cholesterol level.

## Objectives
1. Identify trends in patient demographics (age, gender) for specific diseases.
2. Analyze average blood sugar and cholesterol levels by disease type.
3. Visualize the frequency of hospital visits over time.

## Visualizations

### 1. Disease Prevalence by Gender
- **Type**: Bar Chart
- **Objective**: Displays the count of diseases grouped by gender.
- **Fields**:
  - Axis: Disease_Type
  - Legend: Gender
  - Values: Count of Patient_ID

### 2. Disease Prevalence by Age Group
- **Type**: Bar Chart
- **Objective**: Visualizes how diseases are distributed across age groups.
- **Fields**:
  - Axis: Disease_Type
  - Legend: Age_Group
  - Values: Count of Patient_ID

### 3. Average Blood Sugar Levels by Disease Type
- **Type**: Scatter Plot
- **Objective**: Shows average blood sugar levels correlated with disease types.
- **Fields**:
  - X-Axis: Disease_Type
  - Y-Axis: Average Blood_Sugar_Level
  - Legend: Age_Group

### 4. Average Cholesterol Levels by Disease Type
- **Type**: Line Graph
- **Objective**: Displays average cholesterol levels for each disease type.
- **Fields**:
  - Axis: Disease_Type
  - Values: Average Cholesterol_Level

### 5. Count of Patients by Month
- **Type**: Line Chart
- **Objective**: Visualizes the number of hospital visits over time.
- **Fields**:
  - Axis: Hospital_Visit_Date (formatted as Continuous)
  - Values: Count of Patient_ID

### 6. Disease Distribution by Age Group
- **Type**: Donut Chart
- **Objective**: Highlights the distribution of diseases across different age groups.
- **Fields**:
  - Legend: Age_Group
  - Values: Count of Patient_ID
 
## **Power BI Dashboard**
![Alt text](https://github.com/Abdulwaashim/Healthcare-analysis01/blob/main/Dashboard-img.png)

## Results and Insights

### Achieved Objectives
1. **Trends in patient demographics**:
   - Bar charts for "Disease Prevalence by Gender" and "Disease Prevalence by Age Group" clearly highlight demographic trends.
2. **Blood sugar and cholesterol levels**:
   - Scatter plots and line graphs provide insights into these metrics by disease type.
3. **Hospital visits over time**:
   - Line chart effectively captures the trends in hospital visits over months.

### Suggestions for Improvement
- Correlate Blood Sugar and Cholesterol Levels directly with specific Disease_Types using additional visuals.
- Enhance interactivity with slicers for Age_Group, Gender, and Disease_Type.

## Tools Used
- **Power BI Desktop** for data visualization and analysis.

## How to Reproduce
1. Clone this repository.
2. Open the Power BI file (`Healthcare_analysis01.pbix`).
3. Explore the dashboard and visuals.

## Contact
For questions or feedback, feel free to reach out! 

Thank you for reviewing this project. I hope it provides valuable insights into NCD trends and healthcare metrics.

