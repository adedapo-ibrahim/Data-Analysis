Hospital Operational Crisis Analysis

Author: Adedapo Ibrahim Bayo

Target Audience: Dr. Sarah Obi, COO of City General Hospital

Project Status: Complete

📌 Project Overview
This project involves a deep-dive operational analysis of hospital data to identify the root causes of current crises, including overcrowding, financial strain, and resource mismanagement. By analyzing a dataset of 55,500 patient records, this report moves beyond surface-level symptoms to pinpoint specific operational failures in bed allocation, staff distribution, diagnostic machinery, and clinical prescriptions.

📂 Repository Structure

The analysis is based on the following files:

HOSPITAL OPERATIONAL CRISIS ANALYSIS.pptx: The executive presentation summarizing findings and key actions.

ANALYSIS OF HODPITAL DATA.xlsx: The source data contains patient demographics, billing, and clinical details.

Supporting CSV Extracts:
Data Dictionary.csv: Definitions of dataset variables.
Hospital Versus Patient ID.csv: Patient volume breakdown by facility.
Count of Patient ID Vs Age.csv: Demographic age distribution.
Test Result Vs % Test.csv: Analysis of lab performance and failure rates.
Insurance Vs Billing Amount.csv: Financial breakdown by payer.
Medical Conditions Vs ID.csv: Cross-reference of diagnoses vs. medications prescribed.

📊 Data Context
The analysis covers 55,500 unique patient visits across multiple facilities (including Houston Methodist, Johns Hopkins, etc.). Key Variables Analyzed:
Demographics: Age, Gender, Blood Type.
Clinical: Medical Condition, Medication, Test Results, Admission Type.
Operational: Doctor, Hospital, Room Number, Date of Admission/Discharge.
Financial: Insurance Provider, Billing Amount.

🔍 Key Findings & Insights
1. Capacity Crisis (Bed Allocation Mismatch)
Finding: There is a severe misalignment between ward capacity and patient demographics.
Data: The 0-19 age group accounts for only 1,693 patients, yet the 60+ population exceeds 20,000 patients.
Impact: Pediatric beds are likely sitting empty while geriatric patients face overcrowding and bed shortages.
2. Resource Imbalance (Staffing)
Finding: Workload is not distributed evenly across the hospital network.
Data: Houston Methodist Hospital handles 20,402 patients (approx. 37% of total load), while facilities like Massachusetts General and Northwestern handle fewer than 2,500 patients each.
Impact: Severe burnout at high-volume hubs and wasted labor costs at low-volume zones.
3. Diagnostic Failure (The "Inconclusive" Bottleneck)
Finding: A critical operational failure was identified in laboratory testing.
Data: * Abnormal: 55%
Inconclusive: 35% (19,425 tests)
Normal: 10%
Impact: 35% of all tests failing leads to delayed diagnoses, extended lengths of stay, and billing rejections.
4. Medication Mismanagement (Clinical Errors)
Finding: Analysis of medication vs. condition reveals alarming prescription errors.
Data: Penicillin (an antibiotic) is frequently prescribed for chronic lifestyle conditions, such as hypertension, Diabetes, and Obesity.
Impact: Indicates a severe data entry failure or a critical breakdown in automated prescription protocols.
5. Financial Risk (Revenue Cycle)
Finding: The hospital's cash flow is vulnerable due to the high rate of inconclusive tests.
Data: Medicare is the dominant payer, responsible for $707M in billing.
Impact: With a 35% lab error rate, Medicare claims are at high risk of rejection or audit, freezing a massive portion of revenue.

🚀 Recommendations
Based on the data, the following immediate actions are proposed:
Reallocation: Immediately convert underutilized Pediatric wings into Geriatric/Adult wards.
Staff Balancing: Shift personnel from low-volume centers (e.g., Northwestern) to the critical bottleneck at Houston Methodist.
Lab Audit: Conduct an urgent technical audit of lab equipment to address the 35% "Inconclusive" error rate.
Clinical Review: Halt auto-orders on medications and retrain staff on clinical data entry to stop the prescription of antibiotics for non-infectious chronic diseases.

