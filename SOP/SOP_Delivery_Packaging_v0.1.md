# SOP – Closure: Delivery Packaging

# Purpose
To package final deliverables for client delivery.

# Scope
In: Completed annotations  
Out: Delivery pack

# Owner Role
Annotation Engineer

# Inputs Needed
- Final annotations
- QA reports
- Exports

# Outputs Produced
- Delivery pack
- Export files

# Tools Touched
- CVAT Cloud
- GitHub

# Timebox Range
60+ minutes  
Drivers: export size, QA findings

# Failure Modes
1. Missing exports
2. Wrong format
3. QA not included
4. Incorrect folder structure
5. Incomplete README

# Escalation Rules
Stop delivery if any required file is missing.

# Assumption Ledger
- QA passed
- Exports validated

# Step-by-Step Procedure
1. Export COCO JSON and YOLO  
   Expected Result: Files generated

2. Create delivery pack folder  
   Expected Result: Structured folder created

3. Add README and QA report  
   Expected Result: Documentation complete

4. Final verification  
   Expected Result: Ready for delivery

# Embedded Quality Checks
- Both export formats present
- QA report attached

# Artifacts Produced
- Delivery pack folder

# Example Run (20 Items)
Exports packaged with QA report.

## Failure Case Walkthrough
Missing YOLO export → re-exported → added.
