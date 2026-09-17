# Hospital Operations Analysis Dashboard — City General Hospital

**Author:** Ogaba Faina Ogenyi
**Date:** 2026-09-01

## Project Background

City General Hospital is experiencing operational pressure across patient flow, bed utilization, staff workload, medication management, laboratory processes, and financial performance. Management needs to understand where these pressures originate and which areas require the most urgent operational attention.

This project analyzes available hospital data to identify operational patterns, highlight areas requiring management attention, and present the findings through an interactive Excel dashboard to support evidence-based, board-level decision-making.

## Project Objectives

- Identify patterns contributing to patient congestion and resource pressure.
- Analyze patient flow and admission patterns.
- Examine length of stay and its implications for bed capacity.
- Assess doctor workload, medication usage, laboratory results, and insurance/billing patterns.
- Build an interactive Excel dashboard to support management reporting and decision-making.
- Identify priority areas for operational improvement.
- Recommend practical actions based on the available data.

## Dataset

The project dataset contains patient-level records and hospital-operations information.

The dataset includes:

- Patient ID
- Age
- Gender
- Blood Type
- Medical Condition
- Admission Date
- Discharge Date
- Admission Type
- Length of Stay
- Doctor
- Hospital
- Insurance Provider
- Billing Amount
- Room Number
- Medication
- Test Results

**Admission Type** identifies whether a patient was admitted as **Emergency, Elective, or Urgent**, while **Test Results** identifies each patient's recorded laboratory outcome as **Normal, Abnormal, or Inconclusive**.

Financial fields include **Billing Amount and Insurance Provider**.

## Dashboard Features

### Key Performance Indicators

- **Total Patients — 55,500**
- **Average Length of Stay — 15.51 days**
- **Total Billing — $1,417,432,043.40**

### Dashboard Analyses

- Monthly Patient Flow
- Age-Group Distribution
- Top 10 Doctors by Patient Workload
- Admission Type Distribution
- Average Length of Stay by Admission Type
- Laboratory Test Results
- Medication Usage
- Insurance Performance

The dashboard is designed around the main business questions concerning patient demand and bed capacity, length of stay by admission type, laboratory result reliability, medication and procurement alignment, doctor workload distribution, and billing and insurance performance.

## Interactive Filters

The dashboard includes four slicers:

- Year
- Month
- Admission Type
- Insurance Provider

## Key Findings

### Patient Demand and Bed Capacity

The dataset contains **55,500 patients**, with patient volumes changing across months. This indicates that hospital demand is not evenly distributed throughout the year and should be considered when planning capacity and resources.

Patient demand is unevenly distributed, creating sustained pressure on beds and emergency services. Houston Methodist and Johns Hopkins together account for **57% of total patient volume**, indicating that patient demand is concentrated in a small number of hospitals.

This provides management with evidence that the issue may be bed allocation rather than only the total number of beds — the hospital system may have enough rooms overall, but available rooms may not be located where demand is highest. This imbalance can contribute directly to ER congestion, delayed admissions, and pressure on hospital staff.

### Age Distribution and Capacity Planning

Patients aged **50 and above account for 29,498 patients, approximately 53.1%** of the total patient population.

Older patients drive admissions, accounting for the largest share across hospitals at approximately **27% to 31%**. Because older patients are more likely to need monitoring, mobility support, inpatient care, discharge planning, and longer bed use, the high elderly-patient volume links directly to pressure on beds, staffing, and hospital operations.

This analysis helps address whether capacity planning is adequately accounting for the care needs of this substantial patient group.

### Length of Stay by Admission Type

The overall average length of stay is **15.51 days**.

Average stay by admission type is:

- **Emergency — 15.60 days**
- **Elective — 15.53 days**
- **Urgent — 15.41 days**

Emergency admissions have the highest average stay among the three categories. This comparison helps determine whether particular admission types are placing greater pressure on bed availability and patient flow.

### Laboratory Test Reliability

Laboratory results are distributed as follows:

- **Abnormal — 30,525 (55%)**
- **Inconclusive — 19,425 (35%)**
- **Normal — 5,550 (10%)**

The **35% inconclusive result rate** represents a substantial proportion of recorded laboratory outcomes — more than double the reported retest rate — and may indicate wider problems involving laboratory equipment, sample collection, sample handling, or testing procedures.

This analysis is designed to investigate management's concern about laboratory reliability, since inconclusive results can lead to repeated tests, treatment delays, additional workload, and avoidable costs, connecting laboratory inefficiency directly to staff burnout and patient-flow delays.

### Medication Utilization

The five recorded medications show closely distributed usage volumes:

- **Lipitor — 11,140**
- **Ibuprofen — 11,127**
- **Aspirin — 11,094**
- **Paracetamol — 11,071**
- **Penicillin — 11,068**

The five medications are prescribed at nearly the same rate across medical conditions, suggesting a weak link between diagnosis, prescribing, and procurement. This analysis provides a basis for assessing whether medication ordering is aligned with patient diagnoses, since misalignment can lead to incorrect orders, stock shortages, excess inventory, or wastage.

### Billing and Insurance Performance

Total billing recorded in the dashboard is **$1,417,432,043.40**, with an average billing amount of approximately **$25,539.32 per patient**.

Insurance billing varies across providers:

- **Medicare — approximately $707.47M**
- **UnitedHealthCare — approximately $426.05M**
- **Cigna — approximately $142.79M**
- **Aetna — approximately $141.12M**

Billing averages are similar across hospitals, insurance providers, and patient groups, suggesting that financial losses may not primarily result from low billing or weak payment performance. Instead, the financial pressure may be driven by overcrowding, extended bed use, repeated laboratory tests, and other operating costs — indicating that cost per bed-day and related operational expenses are worth further review.

### Doctor Workload Distribution

The Top 10 Doctors by Patient Workload visualization shows differences in recorded patient workload, for example:

- **Michael Smith — 27 patients**
- **Robert Smith — 22**
- **John Smith — 22**
- **James Smith — 20**

Doctor workload cannot be tracked accurately because the system does not use unique doctor IDs. Without unique identifiers, it is difficult to distinguish doctors with similar names, measure individual workload accurately, or identify staff who may be experiencing excessive patient demand.

## Recommendations

### Capacity and Bed Utilization

- Monitor monthly patient volumes, admissions, discharges, and length of stay to identify periods of elevated resource pressure.
- Track daily bed occupancy alongside admissions and discharges to identify where and when capacity pressure occurs.
- Introduce a referral or transfer system to move patients from overcrowded hospitals to lower-volume hospitals.
- Review delayed discharges, as unnecessary delays may keep beds occupied longer than needed.

### Patient Population and Care Planning

- Use the high proportion of patients aged 50+ when planning inpatient beds, monitoring, support services, and other required resources.
- Reserve adequate geriatric-friendly beds and care support for patients aged 50 and above.
- Align staffing, monitoring, mobility support, and discharge planning around the higher care needs of older patients.

### Laboratory Processes

- Investigate the causes of the 35% inconclusive laboratory result rate.
- Conduct a network-wide audit of laboratory equipment, sample collection, sample handling, and testing procedures.
- Monitor laboratory performance regularly to identify recurring causes of unclear test results and reduce retesting and treatment delays.

### Medication Management

- Introduce diagnosis-linked prescribing controls.
- Align medication procurement and stock ordering with patient diagnoses and treatment needs.
- Review medication-use patterns regularly to reduce incorrect orders, stock shortages, and wastage.

### Workforce and Financial Monitoring

- Assign unique IDs to doctors and other staff to support accurate workload and staffing analysis.
- Use doctor workload data to identify staff pressure and support better workforce allocation.
- Track billing and insurance activity alongside patient volume and length of stay for a broader view of financial and operational performance.
- Identify costs linked to prolonged stays, repeated laboratory tests, and resource pressure.

## Tools & Techniques

- **Microsoft Excel**
- **PivotTables**
- **PivotCharts**
- **Slicers**
- **Data cleaning and transformation**
- **Descriptive analytics**
- **KPI development**
- **Dashboard design and visualization**
- **Patient flow and capacity analysis**
- **Operational and financial analysis**

## Project Files

- **Hospital Operations Analysis Dashboard.xlsx** — Interactive Excel dashboard
- **/datasets/** — Raw data files used for analysis
- **Hospital Operations Analysis Presentation.pdf** — Executive presentation summarizing findings and recommendations
- **README.md** — Project documentation

## How to Run / View

1. Open **Hospital Operations Analysis Dashboard.xlsx** using Microsoft Excel, preferably the desktop version.
2. Enable content if prompted so that PivotTables and slicers can function correctly.
3. Use the dashboard slicers to filter the analysis by **Year, Month, Admission Type, and Insurance Provider**.
4. Review the KPI indicators and charts to explore patient flow, capacity, laboratory, medication, workload, and financial patterns.
5. Refer to the executive presentation for a summarized view of the key findings and recommended actions.

## Contact

**Ogaba Faina Ogenyi**

Email: **Ogaba.faina@gmail.com**
