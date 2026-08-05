# Business Requirements Document (BRD)
**Project Title:** Real Estate Investment ROI Calculator & Market Analysis
**Client:** Vanguard Property Group

## 1. Executive Summary / Business Case
Vanguard Property Group requires a dynamic, data driven tool to standardize their property vetting and aquisition process. The goal is to replace disjointed, manual calculations with a centralized Excel dashboard that accurately projects returns and accounts for historical market data to mitigate acquisition risks.

## 2. Client Profile
**Vanguard Property Group** is a boutique real estate investment firm that specalizes in purchasing single-family homes to hold and manage as long-term rental properties.

## 3. Problem Statement
Current;y, Vanguard's aquistion manager face several opertional challenges during the property evaluation phase:
* **Manual & Inconsistent Evaluation:** Properties are evealuated using "back of the napkin" math and static, disjointed spreadsheets.
* **Lack of Standardization:** There is an inability to objectively compare properties across different ZIP codes due to lack of a standardized tool.
* **Unmitigated Market Risk:** The current process fails to account for historical market stagnation in specific neighborhoods. This recently led to the acquisition of a property that looked promising but resulted in lower than expected returns due to localized market trends.

## 4. Project Objectives
To develop a single, dynamic Excel dashboard that standardizes the property vetting process and provides acquisition managers with instant, data backed investment insights.

## 5. Functional Requirements
The final Excel dashboard must allow acquisition managers to perform the following actions:
* **Variable Input:** Input key financial variables for a specific property, including purchase price, down payment percentage, and interest rate.
* **Automated Calculations:** Instantly view the projected 10-year Return on Investment (ROI) and monthly cash flow.
* **Market Data Integration:** Cross-reference financial projections against historical neighborhood trends by pulling data from Zillow's Home Value Index (ZHVI) and Observed Rent Index (ZORI) datasets.
* **Scenario Stress-Testing:** Stress-test the investment by toggling between best-case and worst-case housing market scenarios.
