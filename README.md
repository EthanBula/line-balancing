# 🧮 Production Synchronization Calculator

This project provides a **Jupyter notebook** to analyze and align production processes with customer demand. It helps calculate key timing metrics and verify whether current capacity meets requirements. This tool is especially useful in **lean manufacturing** and **continuous improvement** environments.

---

## 📈 Problem Description

The goal is to determine:

- Whether the current **cycle time (Tc)** meets the required **takt time (Tt)**
- The number of **lines** and **shifts** required to fulfill demand
- If the current configuration leads to **underproduction** or **excess capacity**

It supports early production planning, bottleneck identification, and alignment of resources to demand.

---

## 🔧 Model Components

### Key Calculations

- **Takt Time (Tt)**: Time available per unit based on demand
- **Cycle Time (Tc)**: Time required to produce one unit
- **Total Demand Fulfilled**: Based on number of lines, shifts, and Tc
- **Production Gap**: Overproduction or underproduction with respect to demand

### Inputs

- Working days
- Daily working hours
- Demand (units)
- Efficiency (%)
- Cycle time (seconds)
- Number of shifts
- Number of lines

---

## 📊 Outputs

- Calculated **takt time** and **cycle time**
- Visuals showing production gaps
- Recommendations to adjust lines or shifts
- Summary table of whether demand is met or not

---

## 🛠️ Technologies Used

- Python 3.x
- [Pandas](https://pandas.pydata.org/)
- [IPython Display](https://ipython.readthedocs.io/en/stable/api/generated/IPython.display.html)
- Math functions (built-in)

---

