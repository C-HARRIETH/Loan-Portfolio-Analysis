# Loan-Portfolio-Analysis

## Overview

This project carries out an analysis to understand the loan portfolio of a Kenyan based microfinance organizaiton.

### Assumptions

- Status `5` = Loan Issued
- Status `6` = Cancelled
- Dates are stored in UTC
- Loan issuance date is determined by the timestamp when status changed to `5`

---

### The project analysis answers the following questions: 

1. How many loans are issued each month?
2. Which team issued more loans (team A or team B)?
3. Which loan agent issued the most loans?
4. Please breakdown sales by loan value (in 1k ranges)
5. How many clients have taken a second loan?
6. On average, how long after payout do clients take a second loan?
7. Which weekday is the most popular to take a loan?
8. Which loan type is the most popular?
9. How many applications do we have per source? Which source brings in the most value?
10. Please select example cases of loans that are not of type CAR and were issued in January. How many such cases are there?
11. What is the average issuance time (from application creation to issuance) monthly by agent? By team?
12. What is the average time between the first status change and loan issuance monthly?
13. How many active loans are there daily?
