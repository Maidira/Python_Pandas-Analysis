# Airline Passenger Satisfaction Panda Analysis

Overview

This project analyzes airline passenger satisfaction data to understand key factors influencing customer experience. The dataset contains 103,904 entries with passenger demographics, flight details, service ratings, and satisfaction levels.

Key Findings

Satisfaction Distribution
  - 56.7% of passengers were neutral or dissatisfied
  - 43.3% reported being satisfied

Key Influencing Factors
Class Matters:
  - Business class has highest satisfaction (72% for business travel)
  - Economy class shows lowest satisfaction (~10% for personal travel)

Service Ratings:
  - satisfied passengers consistently rated all services higher
    - Biggest gaps were in:
    - Online boarding (+1.37)
    - Inflight entertainment (+1.07)
    - Seat comfort (+0.93)

Flight Characteristics:
  - Business travelers had longer flights and higher satisfaction
  - Delays negatively impact satisfaction (satisfied passengers experienced shorter delays)

Demographics:
  - Middle-aged passengers (41-60) were most satisfied
  - Extreme age groups (under 18 and over 60) showed lowest satisfaction
  - Minimal gender difference in satisfaction rates

Technical Details
Data Cleaning
  - Removed duplicates
  - Dropped unnecessary columns ('Unnamed: 0')
  - Handled missing values (310 in Arrival Delay)

Analysis Techniques
  - Descriptive statistics
  - Visualization (countplots, histograms, boxplots, heatmaps)
  - Pivot tables and cross-tabulations
  - Net Promoter Score calculation
  - Service rating comparisons

Key Visualizations
  - Satisfaction distribution by class and travel type
  - Flight distance vs satisfaction
  - Age group satisfaction patterns
  - Service rating comparisons
  - Delay impact analysis

NPS Score
  - The calculated Net Promoter Score proxy is -13.33, indicating more detractors than promoters in the passenger base.

Recommendations
  - Improve economy class experience
  - Focus on service quality (especially online boarding and entertainment)
  - Address needs of younger and older passengers
  - Minimize flight delays and improve delay communication
