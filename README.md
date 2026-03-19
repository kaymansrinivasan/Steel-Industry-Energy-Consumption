# Industrial Energy Consumption Analysis and Cost Optimization

## Overview
This project analyzes industrial energy consumption using 15-minute interval data and maps it to TNB Time-of-Use (TOU) tariffs to identify cost inefficiencies and optimization opportunities.

---

## Objective
- Analyze energy usage patterns  
- Identify cost drivers (Peak vs Off-Peak, Demand)  
- Detect inefficiencies (spikes, low load factor)  
- Simulate cost reduction strategies  

---

## Key Findings
- 81% of energy consumed during Peak hours  
- Maximum Demand: 628.72 kW  
- Load Factor: 0.17 (inefficient usage)  
- 277 demand spikes (~69 hours)  
- Power Factor ≈ 0.80  

---

## Cost Breakdown

| Component        | Cost (RM) |
|----------------|----------|
| Peak Energy     | 284,525 |
| Off-Peak Energy | 52,593  |
| Demand Charges  | 19,050  |
| **Total Cost**  | **356,168** |

---

## Optimization (Simulation)

### Load Shifting
Move part of Peak usage to Off-Peak

### Demand Control
Reduce maximum demand by limiting spikes

---

## Result
Shifting ~20% of Peak load and reducing demand spikes can lead to:

**Estimated Savings: RM 20,000 – RM 25,000 annually**

---

## Tools Used
- SQL (PostgreSQL Embed)
- Python (Pandas, NumPy, Matplotlib)  
- Data Analysis & Simulation  

---

## Author
Kayman Srinivasan
