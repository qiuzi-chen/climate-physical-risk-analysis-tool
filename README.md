# Climate Physical Risk Scenario Analysis Tool

## Overview

An interactive dashboard that quantifies **physical climate risks** across assets and portfolios. It translates complex climate models and geospatial datasets into **clear, decision-ready insights**, enabling users to understand how climate hazards may impact business operations and asset portfolios under different scenarios.

---

## Live Dashboard

👉 https://qiuzi-chen.github.io/climate-physical-risk-analysis-tool/

---

## What This Tool Does

- Quantifies physical climate risks (e.g., floods, droughts, heatwaves)  
- Evaluates risk exposure at both **asset-level and portfolio-level**  
- Models **financial impacts**, using the metric Physical Value-at-Risk (PVaR)  
- Enables scenario comparison across **different climate pathways and time horizons**

---

## Why This Matters

Climate risk is inherently complex, involving uncertainty, spatial variation, and multiple interacting variables.

---

## Methodology

### 1. Scenario-Based Climate Modeling

The tool applies climate scenario analysis method (e.g., RCP pathways) to simulate future climate conditions and their impacts on assets. These scenarios represent different levels of greenhouse gas concentration and temperature increase, allowing users to analyze a range of possible future outcomes.

---

### 2. Risk Assessment Framework

The physical risk assessment follows an event-driven approach, where risks are modeled as specific climate hazard events.

> **Physical Risk Score = Hazard + Exposure + Vulnerability**

- **Hazard:** Intensity and probability of climate events (e.g., extreme heat, flooding)  
- **Exposure:** Degree to which assets are located in affected areas  
- **Vulnerability:** Sensitivity of assets or sectors to those hazards  

---

### 3. Multi-Hazard Risk Assessment

The model covers a range of climate hazards, including:

- Flooding  
- Drought  
- Extreme heat
- Cold wave
- Water stress
- Sea-level rise
- Tropical Cyclone
- Wildfire
- Ecosystem disruption

Each hazard is analyzed using high-resolution geospatial data (10x10km) combined with asset-level information to generate granular risk insights.

---

### 4. Data Integration

The tool integrates multiple datasets, including projection data for climate hazard indicators and social-economic conditions. These inputs are standardized and combined to ensure consistency across risk indicators.

---

### 5. Financial Impact Modeling

Physical risks are translated into financial terms using metrics such as:

- Estimated Cost impacts driven by hazard intensity and duration
- Physical Value-at-Risk (PVaR)  

This enables users to move from **risk identification to financial decision-making**.

---

## Key Features

- Interactive geospatial visualization of climate risks  
- Scenario comparison across multiple climate pathways  
- Portfolio-level risk aggregation  
- Automated data pipelines for scalable analysis  
- Decision-oriented dashboards for non-technical users  

---

## Tech Stack

- Tableau  
- ArcGIS  
- R

