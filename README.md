This project develops a spreadsheet-based financial model to evaluate the lifetime value (LTV) of a customer and the cost-effectiveness of client acquisition strategies for Wealth4All, a financial services firm. 

# Wealth4All: Customer Lifetime Value & Acquisition Cost Model

This repository contains an Excel-based financial model that calculates:
1. Lifetime Value (LTV) of a client 
2. Cost of acquiring clients through marketing campaigns

---

Overview

Part 1: Lifetime Value of a Client
- **Inputs**:  
  - Assets under management (AUM): $150,000  
  - Annual fee percentage: 1% ($1,500/year)  
  - Annual service cost: 6 × $100 = $600  
  - Attrition rate: 25% → Average duration = 4 years  

- **Calculations**:  
  - Profit per year = $1,500 − $600 = **$900**  
  - Lifetime Value = $900 × 4 = **$3,600**  

- **Insight**:  
  - Spending $2,000 to acquire a client is profitable since LTV > CAC.  

---

 Part 2: Client Acquisition
- **Inputs**:  
  - Ad cost: $1,500 for 2,000,000 impressions  
  - Click-through rate: 1.5% → 30,000 clicks  
  - Publisher cost: $0.20/click = $6,000  
  - Mailing cost: $1.50 each = $45,000  
  - Conversion: ~0.03 (3%) from calls  

- **Outputs**:  
  - Clients acquired ≈ 18  
  - Cost per client ≈ **$2,833**  
  - Net gain per client = LTV − CAC = **$767**  

---
 How to Use
1. Open **Wealth4all project.xlsx**.  
2. Modify **Inputs** tab (AUM, fee %, service costs, ad spend, conversion rates).  
3. Check **Outputs** tab for:  
   - Lifetime Value (LTV)  
   - Client Acquisition Cost (CAC)  
   - Profitability analysis  

The model can be extended to include:
- Multiple customer types (different asset/service profiles)  
- Multiple marketing strategies with unique costs & responses  
- Sensitivity and scenario analysis  
- Optimization under service-hour constraints  
