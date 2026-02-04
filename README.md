# Deloitte-Data-Analytics-Job-Simulation
# Deloitte Data Analytics Virtual Experience (Forage)

## Overview
This repository contains my work for the Deloitte Data Analytics Virtual Experience Program hosted on Forage.  
The project focuses on analyzing business data using Excel and Tableau to generate actionable insights.

Organization: Deloitte (via Forage)  
Tools Used: Microsoft Excel, Tableau  
---

## Project Objectives
- Classify employee compensation equality scores
- Identify fairness and discrimination patterns
- Analyze machine downtime using telemetry data
- Build interactive dashboards for business decision-making
---

## Task 1: Downtime Analysis (Tableau)

### Key Steps:
- Imported telemetry JSON data into Tableau
- Created a calculated field "Unhealthy"
  - Assigned 10 minutes for each unhealthy status
- Built visualizations:
  - Down Time per Factory
  - Down Time per Device Type

### Dashboard Features:
- Interactive filtering by factory
- Device-level downtime updates dynamically
- Clear visualization for non-technical stakeholders

## Task 2: Equality Score Analysis (Excel)

### Dataset Includes:
- Factory
- Job Role
- Equality Score (-100 to +100)

### Classification Logic:
- Fair: -10 to +10
- Unfair: < -10 or > +10
- Highly Discriminative: < -20 or > +20

### Outcome:
Raw equality scores were classified into meaningful business categories to highlight potential compensation risks.
---

## Key Insights
- Certain factories showed significantly higher downtime
- Specific device types contributed most to downtime
- Data classification helped identify areas needing HR policy review
---

## Files in This Repository
- Excel analysis file
- Dashboard screenshot
- Project report (PDF)

