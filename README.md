# COVID-19 Data Analysis & Visualization (R)
This project presents an end-to-end data analysis pipeline to explore COVID-19 trends across major Australian states using publicly available data.
The workflow includes data ingestion, cleaning, transformation, visualization, and interactive dashboarding to uncover meaningful patterns in pandemic dynamics.

# Objectives
- Analyze COVID-19 case and death trends across states
- Compare state-wise pandemic impact
- Normalize metrics based on population for fair comparison
- Identify temporal patterns and trends
- Build an interactive dashboard for data exploration

# Dataset
- Source: COVIDLive (Australia)
- Time Period: 2020 – 2025
- Features:
  - Daily case counts
  - Death counts
  - State-level data

# Project Pipeline
Data Collection → Data Cleaning → Feature Engineering → Analysis → Visualization → Dashboard

# Tools & Technologies
- R
- tidyverse (dplyr, tidyr)
- ggplot2
- plotly
- shiny

# Key Insights
- Significant variation in case trends across Australian states
- Population-normalized metrics reveal different risk patterns
- Clear waves of infection over time
- Death rates show lagging trends compared to case spikes

# Business / Policy Relevance
- Helps policymakers understand regional risk patterns
- Supports data-driven decisions during health crises
- Enables comparison of outbreak severity across regions
- Demonstrates how data pipelines can support public health analytics

# Project Structure
covid-data-analysis-r/
│── data/        # Raw dataset
│── scripts/     # Data ingestion, analysis, and visualization scripts
│── README.md
│── Report.pdf

# How to Run
1. Clone the repository  
2. Open scripts in RStudio  
3. Run analysis scripts sequentially  
4. Launch Shiny app for interactive dashboard  

# Future Improvements
- Add real-time API data ingestion
- Integrate predictive models (time series forecasting)
- Deploy dashboard online
