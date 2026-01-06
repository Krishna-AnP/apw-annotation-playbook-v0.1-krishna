# SOP – Planning: Capacity and Timeline Estimation

# Purpose
To estimate annotation throughput and delivery timeline.

# Scope
In: Calibration data  
Out: Time and capacity estimate

# Owner Role
Annotation Engineer

# Inputs Needed
- Calibration annotation metrics

# Outputs Produced
- Throughput estimate
- Timeline estimate

# Tools Touched
- CVAT Cloud
- Estimator Template

# Timebox Range
30–45 minutes  
Drivers: calibration accuracy

# Failure Modes
1. Inaccurate calibration
2. Underestimated QA time
3. Ignored rework rate
4. No buffer included
5. Unrealistic throughput

# Escalation Rules
Stop if estimates ignore QA or buffer.

# Assumption Ledger
- Single annotator
- Uniform image complexity

# Step-by-Step Procedure
1. Annotate 10 calibration images  
   Expected Result: Calibration data captured

2. Record start/end time  
   Expected Result: Time metrics available

3. Calculate throughput  
   Expected Result: Images/hour computed

4. Apply QA, rework, buffer factors  
   Expected Result: Final timeline estimate

# Embedded Quality Checks
- QA ≥20%
- Buffer ≥10%

# Artifacts Produced
- Filled estimator template

# Example Run (10 Items)
10 images annotated in 50 minutes.

# Failure Case Walkthrough
QA time ignored → estimate revised → approved.
