# Retail Analytics Dashboard — Executive Decision Support
### Applied Data Science · Analytics · Forecasting · KPI Design

---

## Overview
This project specifies an end‑to‑end **executive decision-support dashboard** for a Nigerian retail liquor business.  
The system is designed to operate under real-world constraints — irregular power supply, fragmented POS systems, inconsistent data, inflation volatility, and low analytics maturity.

The dashboard integrates **descriptive, diagnostic, predictive, and prescriptive** analytics into a unified tool for leadership decision‑making.

---

## Problem Context
Nigeria’s retail environment presents unique challenges:

- **Frequent power outages** causing unreliable POS and reconciliation  
- **Inconsistent and inaccurate records** due to manual processes  
- **High shrinkage risks**, including theft and administrative error  
- **Currency and inflation volatility** impacting margins and pricing  
- **Fragmented SKU and supplier data** with no unified governance  

These conditions require a resilient system that *reduces ambiguity*, standardizes metrics, and supports executives with clear decision-ready insights.

---

## What I Built
A full specification for a multi-layered analytics system featuring:

### **1. Role-Aligned KPI Structure**
- CEO: enterprise momentum, growth patterns, risk signals  
- Finance: margin health, cost/mix drivers, GMROI  
- Operations: stock cover, supplier reliability, shrinkage  
- Marketing: promotion uplift, event-driven demand patterns  

### **2. Analytics Continuum**
**Descriptive → Diagnostic → Predictive → Prescriptive**

Examples:
- Sales trends → margin bridges → SKU forecasts → reorder recommendations  
- Shrinkage variance → root-cause clusters → operational risk forecasts → corrective actions  

### **3. Governed Data Foundation**
- SKU standardization  
- Reconciled measures for sales, cost, stock  
- Data dictionary + access rules  
- Clean aggregation paths (SKU → Brand → Category → Enterprise)

### **4. Forecasting and Inventory Logic**
- SKU‑store level forecasts (trend, seasonality, event effects)  
- MAPE‑based model reliability scoring  
- Reorder Points (ROP) incorporating demand and lead-time variability  

### **5. UX & Visualization Principles**
- Mobile-first design for outage environments  
- Lightweight visuals for unreliable connectivity  
- Consistent KPI → diagnostics → action workflow  

---

## Analytical Techniques

- KPI design linked to strategic leadership objectives  
- Time‑series forecasting with uncertainty bands  
- Margin decomposition (price, cost, mix)  
- Shrinkage diagnostics based on Nigerian retail evidence  
- Supplier performance scoring  
- Promotional uplift analysis  
- Robust hierarchical aggregation  

---

## Key Outputs
- 3,000‑word dashboard system specification  
- KPI and formula dictionary  
- UX layout blueprint  
- Metric derivations (GMROI, Days of Cover, Stockout Rate, etc.)  
- Recommended visualization hierarchy  
- Design guardrails for low-infrastructure environments  

---

## Impact
The project demonstrates the ability to:

- Translate domain complexity into structured analytical systems  
- Build decision workflows for executive users  
- Design KPIs that reflect real operational constraints  
- Create forecasting and diagnostic logic that supports action  
- Communicate system design clearly and at an executive level  

This is a systems-thinking project that blends **data science, business understanding, and real-world operational insight**.

---

## Future Work
- Full prototype implementation in Python/Power BI/Streamlit  
- Automated data ingestion and reconciliation  
- Expansion of prescriptive models  
- Interactive scenario simulation tools  

