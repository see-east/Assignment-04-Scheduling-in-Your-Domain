# Assignment-04-Scheduling-in-Your-Domain
ISYS 320U: Assignment 04

## 24-Hour Delivery Crew Scheduling Optimization

A linear programming model built in Python using PuLP to optimize logistics crew scheduling across a full 24-hour operational day. This project was completed as part of an operations research and decision modeling course.

---

### Project Overview

This notebook models the problem of assigning crew units to six 4-hour shift periods to meet delivery demand while managing staffing costs. The model evolves across three stages — cost minimization, what-if demand analysis, and service maximization — reflecting a real stakeholder objective change mid-project.

---

### Files

- Main Jupyter notebook with all models, charts, and analysis
- CSV base scenario data generated via Claude (Anthropic) 

---

### What-If Scenario

Mid Morning (8am–12pm) demand was increased by 25% (6 → 8 units) to simulate an unplanned demand surge. The isolated cost impact confirmed that lean scheduling carries no buffer against variability.

---

### Key Takeaway

Time-indexed scheduling constraints are non-transferable across periods — slack in one shift cannot offset a shortfall in another. This makes the choice of objective function (cost vs. service) a strategic business decision, not just a modeling preference.

---

## Data Note

Scenario data including time periods, demand requirements, and cost-per-unit values was generated using Claude (Anthropic), a large language model, to simulate a realistic 24-hour logistics crew scheduling environment for cost minimization analysis.

