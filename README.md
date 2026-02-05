# Hypertension-Patient-Care-Analytics
![](medical-image.jpg)
## Introduction
Hypertension is a major public health condition that requires continuous monitoring, effective treatment, and regular follow-ups to prevent severe complications.
This project analyses hypertension patient care data from a healthcare case study within the healthcare industry. It focuses on patient visit patterns, treatment outcomes, costs, and follow-up needs over a 12 month period.
The aim of this analysis is to generate insights that support better healthcare planning, improved resource allocation, and more effective management of hypertension patients. 
## Problem Statement

Healthcare providers face challenges in managing hypertension patients due to:
- High patient volumes
- Varying treatment effectiveness
- Inconsistent follow-up compliance
- Rising treatment costs
## The key business questions this analysis addresses are:
-	How many patients and visits are being recorded over time?
- How successful are current hypertension treatments?
-	Which severity levels require the most follow-up care?
-	How do treatment costs vary by severity?
-	Are there specific demographic or location-based patterns that affect outcomes?

This analysis aims to provide data-driven insights to support improved hypertension care planning and monitoring.
## Data Sourcing
The dataset used in this project is a simulated healthcare dataset designed for analytical and educational purposes.
## Dataset details:
Source: Simulated healthcare case study
- Time period: January 2014 – December 2014
- Key fields include:
-	Patient ID
-	Patient Visit ID
-	Patient Visit date
- Gender
- Age
- Location
- Doctor ID
- Disease
- Hypertension severity level
-	Treatment type
- Treatment cost
- Visit status
- Follow-up Required
- Patient Success Rate
## Data Transformation & Cleaning
Several data preparation steps were performed to ensure accurate analysis:
- Removed duplicate records
- Created unique identifiers for patients,Location and Treatment
-	Standardised date formats and created a date table
-	Categorised patients into age groups
-	Validated treatment cost values
-	Created calculated measures using DAX (e.g. completed visits, treatment success rate, follow-up percentage)
  These steps ensured the dataset was clean, consistent, and suitable for analysis in Power BI.
 	## Key Metrics (KPIs)

The following KPIs were developed to measure performance:
-	Total Visits: 3,000
- Total Patients: 499
- Treatment Success Rate: 50%
-	Completed Visits: 1,015
-	Follow-Up Required: 48%
-	Average Treatment Cost: £26K
