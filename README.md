# Drug Demand Prediction for Dengue and Malaria — PAHO Project

## Overview
This project aims to predict the monthly demand for preventive and treatment drugs for dengue and malaria across Venezuela, Colombia, and selected northern Brazilian states — Acre, Amapá, Amazonas, Pará, Rondônia, Roraima, and Tocantins.
The work supports PAHO’s (Pan American Health Organization) efforts in optimizing drug allocation and forecasting regional health needs based on environmental and migration patterns.

## Project Objectives
- Forecast monthly preventive drug requirements for dengue and malaria.
- Incorporate migration and weather patterns to identify regions with rising disease risk and changing population exposure.
- Support public health supply planning by generating early warning signals for potential drug shortages or surges in demand.

## Methodology
### 1. Data Sources
- Migration data – population movement trends between and within countries.
- Weather and climate data – precipitation, temperature, humidity, and extreme weather indicators.
- Health data – historical malaria and dengue case counts/drug usage data.
- Geospatial data – regional boundaries (states and municipalities) for spatial joins and visualization.

### 2. Data Processing
- Temporal granularity: Monthly (2010–2024).
- Spatial granularity: State-level for Brazil; equivalent administrative units for Venezuela and Colombia.
### Cleaning & alignment:
- Standardized timestamps to monthly intervals.
- Merged datasets based on region and month.
- Created lag features (e.g., 1–3 month migration and rainfall lag) to model delayed effects on disease spread.
