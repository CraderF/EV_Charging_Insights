# EV_Charging_Insights
Exploratory Data Analysis of EV charging and load-shifting behavior using energy consumption data to find insights on peak hours, charging patterns, and optimization opportunities. 

## Project Overview
This project explores workplace EV charging behavior to find usage inefficiencies, identify load-shifting opportunities and measure how COVID-19 influenced energy consumption, efficiency, and user behavior.  
Using Python, the analysis quantifies trends across pre-COVID, during-COVID, and post-COVID periods, giving a look into infrastructure utilization and optimization strategies.

## Questions we answered
What are the peak vs off-peak charging behaviors?
How does a market disruption (Covid-19) impact EV charging behaviors?
How much charging behavior is over-provisioned?

## Findings
| Period | Avg Efficiency | Avg Cost per Session ($) | Over-Provisioned (%) |
|:--|:--:|:--:|:--:|
| **Pre-COVID** | 0.71 | 1.30 | 71.3% |
| **During COVID** | 0.56 | 1.22 | 84.0% |
| **Post-COVID** | 0.56 | 1.32 | 74.3% |
| **Overall** | 0.65 | 1.27 | 75.7% |

## Conclusion
- **Efficiency dropped 20%** during COVID and remained low post-pandemic.  
- **Over-provisioning rose sharply**, with ~75% of sessions flagged as idle-heavy.  
- **Peak charging hours (7–10 AM)** consistently showed reduced efficiency.  
- **Costs fell slightly during COVID** but rebounded afterward, aligning with usage recovery.  

- **Peak Load Shifting:**  
  Shifting 15–20% of morning charging sessions to off-peak hours could reduce total peak demand by ~10–15%.
- **Behavioral Change Persistence:**  
  Efficiency did not return to pre-pandemic levels, suggesting a long-term change in workplace charging patterns.
- **Infrastructure Optimization:**  
  High over-provisioning (75%+) indicates potential for idle-time fees or smarter scheduling systems.

## Tools Used
- Python 3.12
- pandas, numpy, matplotlib, seaborn  
- Jupyter Notebook 
