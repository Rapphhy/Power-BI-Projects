# Healthcare Waitlist Dashboard

## Overview

This Power BI dashboard provides actionable insights into healthcare waitlists, enabling better resource allocation, operational efficiency, and patient experience improvement. It analyzes trends in waitlists across case types, age profiles, and specialties, offering stakeholders a data-driven approach to decision-making.

## Data Cleaning and Preparation
The data underwent rigorous cleaning and transformation to ensure accuracy and consistency:
- **Date Transformation**:
  - Used DAX formulas to convert date columns from text to the date data type for proper analysis.
- **Table Appending**:
  - Combined multiple tables (`Inpatient`, `Outpatient`, etc.) into a unified dataset using Power BI’s **Append Queries** feature.
- **Null Handling**:
  - Replaced null values in key columns with appropriate default values or removed rows with incomplete data.
- **Custom Calculations**:
  - Performed calculations for average and median patient wait times using DAX to generate dynamic and accurate insights.

## Key Features
- **Total Wait List Comparison**:
  - Visualizes the latest month's wait list alongside the previous year's data for comparison.
- **Key Indicators**:
  - Displays the median patient wait list times across age profiles (0–15, 16–64, 65+).
- **Time Band by Age Profile**:
  - Highlights patient wait times categorized by age groups and waiting periods (e.g., 0–3 months, 3–6 months).
- **Top 5 Specialties by Wait Time**:
  - Identifies specialties with the highest median wait times, such as Accident & Emergency and Dermatology.
- **Case Type Distribution**:
  - Visual breakdown of cases into Day Case, Inpatient, and Outpatient categories.
- **Trend Analysis**:
  - Tracks historical trends of wait lists for Day Case, Inpatient, and Outpatient case types.

## Data Insights
1. **Overall Trends**:
   - An increasing trend in waitlists over the years, particularly for inpatient cases, highlights the need for increased capacity or improved efficiency.
   
2. **Case Type Performance**:
   - Outpatients represent a significant proportion of the total waitlists, indicating potential bottlenecks in outpatient services.

3. **Specialty Focus**:
   - Specialties like Accident & Emergency and Dermatology have the highest average waitlists, signaling areas where resource allocation can have the most impact.

4. **Age Profiles**:
   - The 0–15 and 16–64 age groups dominate the waitlists, but older patients (65+) show a longer average wait time, suggesting prioritization for senior care may be required.


## Use Cases
1. **Strategic Resource Allocation**:
   - Healthcare administrators can identify specialties and case types requiring immediate resource adjustments, such as staff, equipment, or infrastructure.

2. **Patient Prioritization**:
   - By analyzing age profiles and time bands, care providers can prioritize patients based on urgency and demographic need.

3. **Performance Monitoring**:
   - Historical trend analysis helps track improvements or regressions in healthcare delivery performance.

4. **Predictive Planning**:
   - Leveraging historical data trends, stakeholders can anticipate future patient demand and proactively plan resources.
   

   ## 5️⃣ Share Your Insights 💡
Run your analyses, share queries, and help others learn! ✨ Don't forget to **star** this repository if you find it helpful!


Cheers!!