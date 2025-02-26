#
# Google Fiber Case Study:
## How Can Customer Service Reduce Call Volumes?

![googlefiber_logo](./google_fiber_logo.png)

**Author:** Kevin Leung

**Date:** 2025-02-20

#

**Business Intelligence Contents:**

1. Capture
2. Analyze
3. Monitor

#

[**Stakeholder Requirements Document**](https://github.com/kleung157/Google_Fiber_Case_Study_Business_Intelligence/blob/93ac7705e88a1327577324be21f1e8279280a4ba/stakeholder_requirements.pdf)

[**Project Requirements Document**](https://github.com/kleung157/Google_Fiber_Case_Study_Business_Intelligence/blob/93ac7705e88a1327577324be21f1e8279280a4ba/project_requirements.pdf)

[**Strategy Document**](https://github.com/kleung157/Google_Fiber_Case_Study_Business_Intelligence/blob/93ac7705e88a1327577324be21f1e8279280a4ba/strategy.pdf)

#

## 1. Capture
**Overview:**

Google Fiber provides fiber optic internet to people and businesses. The customer service division monitors and improves customer satisfaction. The goal is to understand how often customers phone customer support again after their first inquiry and exploring trends in repeat callers. The insights could then be used to reduce call volumes.

**Business Task:**

Explore repeat caller trends and provide actionable insights to empower stakeholders to identify opportunities for call volume reduction.

**Considerations:**

What is the frequency of repeat calls from customers?

What types of problems generate the most repeat calls?

Which market city recieves the most repeat calls?

#

## 2. Analyze

Customer dataset was cleaned, anonymized and approved including: number of calls, number of repeat calls after first contact, call type, market city, and date. 

The columns market_1, market_2, market_3 indicate 3 different city service areas the data represents. 

Five problem types listed, type_1 is account management, type_2 is technician troubleshooting, type_3 is scheduling, type_4 is construction, and type_5 is internet and wifi 

Dataset repeats calls over seven-day periods 

Initial contact date is listed as contacts_n and other call columns are contact_n_number of days since first call. Ex. contacts_n_6 indicates 6 days since first contact 

Utilized SQL in Google BigQuery to UNION multiple datasets into a single, unified source to prepare for analysis.

[Merged Dataset](https://github.com/kleung157/Google_Fiber_Case_Study_Business_Intelligence/blob/ec9e4e4074baba834d7b90dd1b3bc1ecbc51722f/google_fiber_dataset_merged.csv) 

## 3. Monitor

#### Dashboard:
https://public.tableau.com/views/GoogleFiberDashboard_17400943179500/HomeDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

![google_fiber_dashboard](https://github.com/kleung157/Google_Fiber_Case_Study_Business_Intelligence/blob/93ac7705e88a1327577324be21f1e8279280a4ba/google_fiber_dashboard.png)
