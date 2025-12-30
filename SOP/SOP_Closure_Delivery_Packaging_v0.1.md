# SOP – Delivery Packaging (v0.1)

# Purpose
Define how final annotation outputs are packaged and prepared for delivery.

# Scope
In: Final exports and documentation

# Owner Role
Project Operator

# Inputs Needed
- Approved annotation jobs
- Final QA reports
- Exported annotation files

# Outputs Produced
- Delivery package
- Final export files

# Tools Touched
- CVAT Cloud
- GitHub

# Timebox Range
15–30 minutes

# Failure Modes
- Missing export files
- Wrong format delivered
- Unapproved data delivered

# Escalation Rules
Stop delivery if QA approval is missing

# Assumption Ledger
- QA is completed
- Export format agreed

# Step-by-Step Procedure

1. Verify all jobs are approved  
   Expected result: No pending rework

2. Export final annotations  
   Expected result: Correct format downloaded

3. Organize delivery folder  
   Expected result: Clean structure

4. Verify files open correctly  
   Expected result: No corrupted files

# Embedded Quality Checks
- File names correct
- Formats verified

# Artifacts Produced
- Final export ZIP

# Example Run
10 images exported successfully

# Failure Case
Wrong format → re-export before delivery
