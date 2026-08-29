# Week 4 — Analyst Lab — HealthConnect

AnalystLab Africa Experience Lab — Data Analytics track — Week 4 (HealthConnect Project Kickoff & Problem Understanding).

From Week 4 onward, all internship tracks contribute to a single shared fictional project: **HealthConnect Clinic**, an appointment-based healthcare provider struggling with missed appointments, wasted slots, and unclear no-show drivers. This repo contains the Data Analytics track's Week 4 contribution.

## Contents

```
week-4/
├── analysis/
│   └── HealthConnect_Initial_Analysis.ipynb   # Initial Analysis Document (executed, no errors)
├── data/
│   ├── HealthConnect_Appointment_Data.csv         # Appointment dataset (5,000 records)
│   ├── HealthConnect_Data_Dictionary.xlsx         # Variable definitions
│   ├── HealthConnect_Data_Dictionary - Data Dictionary.csv
│   └── HealthConnect_Clinic_Knowledge_Base.docx.pdf
└── Week4_Project_Summary.docx                 # Concise Week 4 summary + Week 5 focus
```

## What's in the analysis notebook

`analysis/HealthConnect_Initial_Analysis.ipynb` covers, in the order required by the Week 4 brief:

1. Dataset Overview
2. Data Quality Assessment
3. Identification of Important Variables (evidence-based — no-show rate tested by segment for every candidate variable)
4. Business Questions
5. Proposed KPIs (justified and linked to business questions — not yet calculated, per Week 4 scope)
6. Initial Analysis Approach
7. Assumptions, Limitations, Risks and Dependencies

**Key finding:** of all candidate variables, only `previous_no_shows`, `booking_lead_days`, and `distance_to_clinic_km` show meaningful, evidence-backed separation between Attended and No-Show outcomes. Reminders show only a weak effect — notably weaker than the business scenario's framing implies. Appointment logistics and demographics show no meaningful separation.

## Data source

Original resources provided by AnalystLab Africa for the HealthConnect Experience Lab. Files are unmodified from their source; any cleaned/derived data will be saved separately as work progresses.

## Week 5 focus

- Calculate and visualise the five locked KPIs
- Test whether the three strongest variables hold up in combination (confounding check)
- Align outcome-variable definition with the Data Science track before their modelling begins
