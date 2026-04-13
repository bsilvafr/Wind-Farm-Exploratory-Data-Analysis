# Wind Power Generation Analysis

## 🎯 About the Project
This project provides a comprehensive efficiency analysis of wind power generation across four distinct locations over a one-year period. By correlating operational data with atmospheric variables, the study identifies performance drivers, hemispheric positioning, and density-dependent efficiency gaps.

## 🧮 Data Integrity & Initial Assessment
• Data Integrity: The dataset was audited and confirmed to have zero missing values, ensuring a statistically robust foundation for all subsequent analyses.

• Baseline Production: The study initiated with a comparative analysis of power output across all sites to establish the baseline generation capacity for each location.

<img width="1670" height="658" alt="image" src="https://github.com/user-attachments/assets/aa06ac3c-ad3e-4159-8683-91f126c3eb07" />

## 🔍 Key Analytical Phases

### 🔹1. Thermal Impact & Hemispheric Identification
A study on the relationship between ambient temperature and turbine efficiency revealed a significant performance degradation during peak temperature months.

• Seasonal Correlation: The performance dip occurred consistently in the middle of the calendar year.

• Geographic Inference: This thermal response confirms that all locations are situated in the Northern Hemisphere, where the highest temperatures occur between June and August.

• The Winter Efficiency Paradox: Although wind resource availability peaks in winter, the turbines' capacity to convert this surplus energy does not scale proportionally. This suggests aerodynamic saturation or mechanical control limits that prevent the system from fully exploiting high-resource periods.

<img width="1668" height="646" alt="image" src="https://github.com/user-attachments/assets/b427e9a2-7a8b-4668-8557-b3dac3599e99" />

### 🔹2. Atmospheric Density as a Performance Driver
• Positive Correlation: Efficiency is positively correlated with air density. Since cold air is denser, winter provides a higher "mass flow" through the rotor.

• Physical Reinforcement: The higher production observed in winter is a direct result of increased air density, which provides more kinetic energy for the same wind speed compared to summer.

<img width="1667" height="647" alt="image" src="https://github.com/user-attachments/assets/b664df38-d43c-4777-8c18-57d25c3112f8" />

### 🔹3. Aerodynamic Shear & Seasonal Directional Stability
• Wind Shear Profile: Analysis of the vertical wind gradient (10m to 100m) showed how velocity changes impact rotor torque.

• Directional Resource: Using radar plots to compare High and Low Density regimes, we found that even when wind aligns with dominant high-resource sectors during High Density periods, the Efficiency Gap remains significantly wider. This confirms that higher wind availability in winter does not translate to proportional efficiency gains, regardless of the wind's direction, suggesting aerodynamic or mechanical saturation.

<img width="1684" height="455" alt="image" src="https://github.com/user-attachments/assets/ad40c1ed-0f97-4302-b0d9-a97104c25e58" />

### 🔹4. Advanced Power Curve Modeling
To ensure an unbiased comparison between Theoretical Potential and Actual Performance, we utilized LOWESS (Locally Weighted Scatterplot Smoothing).

• Density Partitioning: The analysis was split into High Density and Low Density regimes to isolate atmospheric effects from mechanical performance.

• Operational Integrity: Across all locations, low efficiency events and operational downtime were significantly more frequent during low-density periods.

• Site Diagnostics: 
   
    - Location 1: Closest alignment between the real-world curve and the theoretical model (highest integrity).
    - Location 2: Highest deviation from the theoretical curve (most significant performance loss).
    
<img width="1669" height="674" alt="image" src="https://github.com/user-attachments/assets/b6f0f186-a3a4-4522-91ef-c3f18a8f26ef" />

## 🏆 Final Benchmarking & Reliability
The study concluded with a multi-metric dashboard evaluating:

• Operational Efficiency(90th percentile standard): Technical conversion quality.

• Capacity Factor: Actual energy delivery

• Absolute Efficiency Gap: Quantification of lost energy resource.

<img width="1673" height="477" alt="image" src="https://github.com/user-attachments/assets/c05ece41-470e-4e6f-9edc-ccaa361c71eb" />

### Stability & Error Analysis
The benchmarking includes error bars representing the stability of each location across the studied timeframe. By maintaining the split between high and low densities, we captured the distinct physical behaviors of the turbines under different atmospheric states.

## 📌 Conclusion
This project represents a deep dive into wind power diagnostics, moving beyond simple production metrics to explore the underlying atmospheric physics. More than just calculating output, the focus was on understanding how temperature, density, and direction interact to create efficiency gaps.

The analysis highlights that there is no "one-size-fits-all" performance profile; each site responds differently to seasonal shifts. By partitioning data into density regimes and using directional mapping, we’ve moved from raw data to actionable intelligence, providing a clear roadmap for where to investigate mechanical issues or terrain-based losses.
