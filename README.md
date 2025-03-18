# Optimizing Hospital Operations: A Data Analytics Approach
## Introduction
This project is carried out to simulate how hospitals in Nigeria can leverage data analytics to monitor and improve their operations. Using SQL, Power BI, and Python, the dashboard tracks key performance indicators (KPIs) across four main areas: hospital overview, patient flow, resource utilization, and financial performance. The data used is synthetic, generated to mimic real-world hospital scenarios.

## Table of Contents
- Project Overview (#project-overview)
- Dashboard Features (#dashboard-features)
- Technologies Used (#technologies-used)
- Data (#data)
- Dashboard (#screenshots)
- Insights
- Recommendations
  
## Project Overview
Hospitals in Nigeria often face challenges in tracking patient care, resource allocation, and operational efficiency due to limited access to real-time data. This dashboard aims to address that by providing a tool to monitor critical KPIs, enabling data-driven decision-making. Although built with synthetic data, the project demonstrates how analytics can transform hospital management.



## Tools Used
- SQL: For querying and aggregating hospital data.
- Python: For generating synthetic hospital data (using Pandas, NumPy, Faker).
- Power BI: For building interactive visualizations and dashboards.


## Data
The dashboard uses synthetic data generated with Python’s Faker library to simulate realistic hospital operations, including:
- Patient demographics and admissions.
- Staff assignments and shifts.
- Financial transactions (billing and expenses).
- Equipment and bed usage.
This data mimics real-world scenarios but is entirely fictional, ensuring privacy and compliance.

## Dashboard Features
The dashboard consists of four interactive pages:
- Overview: High-level metrics like total patients, average length of stay, bed occupancy, and total revenue.
- Patient Flow & Trends: Visualizes admissions, discharges, patient demographics, and top diagnoses.
- Resource Utilization: Tracks bed occupancy by department, staff-to-patient ratios, and equipment usage.
- Financial Performance: Monitors revenue, expenses, cost per patient, and profitability trends.
  
<img width="745" alt="Screenshot 2025-03-18 140952" src="https://github.com/user-attachments/assets/18da217e-c69c-400c-9da3-3a5ac3be681f" />
<img width="746" alt="Screenshot 2025-03-18 140838" src="https://github.com/user-attachments/assets/15a59860-b381-4acd-bcbf-195493e351df" />
<img width="746" alt="Screenshot 2025-03-18 140748" src="https://github.com/user-attachments/assets/a5cd4b82-0454-4ecd-bffc-6e2653259901" />
<img width="744" alt="Screenshot 2025-03-18 140917" src="https://github.com/user-attachments/assets/a4dcd060-4cb4-4b37-a8ba-0d66032471f8" />

## Key Insights from Analysis
-	ER & ICU have high bed occupancy rates (91.67% and 100%, respectively), while General Ward has only 47.37% occupancy, indicating inefficient bed distribution.
-	Peak admission hours are 3 AM and 7 AM, with the highest patient volume on Tuesdays and Wednesdays, requiring additional staff coverage during these periods.
-	ER has the shortest consultation wait time (34 minutes), but Pediatrics, Cardiology, and ICU patients wait over 100 minutes, leading to patient dissatisfaction.
-	Cardiology nurses handle the highest patient load (1,837 patients per nurse), followed by ICU (1,710) and Pediatrics (1,440), increasing staff burnout risks.
- Night shift staffs work an average of 9 hours per shift
- Some medical equipment such as the Infant Warmer, Oxygen Concentrator, and Ventilator has exceeded recommended usage hours, increasing breakdown risks and potential equipment failure during critical care.
- NHIS and Private HMO patients have the lowest profit margins (17.6–17.9%), making them less financially sustainable compared to self-pay patients. Although NHIS patients generate a higher average bill per patient (₦161K) than self-pay patients (₦146K), higher associated expenses and lower reimbursement rates limit overall hospital profitability.


## Final Summary of Key Actions
- Reallocate 20 beds from General Ward to ER & ICU to reduce overcrowding. Expand ICU by converting underused wards into step-down units for stable patients.
- Hire additional ER & ICU doctors and nurses to reduce patient wait times and prevent staff burnout.
- Implement digital queue management to streamline check-ins and reduce consultation wait times.
- Perform preventive maintenance on overused Infant Warmers, Oxygen Concentrators, and Ventilators to prevent equipment failure.
- Rotate underutilized equipment, such as X-ray machines, to high-demand departments for better utilization.
- Adjust staffing schedules to ensure more staff are available during peak admission hours (3 AM and 7 AM) and high-volume days (Tuesdays & Wednesdays).
- Increase self-pay services by marketing premium healthcare options, including VIP consultation services, to attract more self-pay patients and improve revenue.
- Negotiate higher NHIS reimbursement rates to increase hospital profitability and reduce reliance on low-margin insurance patients.
