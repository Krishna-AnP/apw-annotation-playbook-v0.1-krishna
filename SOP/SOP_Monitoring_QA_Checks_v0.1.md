# SOP – QA Checks (v0.1)

# Purpose
Ensure annotation quality is checked regularly and consistently.

# Scope
In: Ongoing annotation work  

# Owner Role
QA Reviewer

# Inputs Needed
- Annotated jobs
- Label specification
- QA report template

# Outputs Produced
- QA findings
- Rework requests

# Tools Touched
- CVAT Cloud
- GitHub documentation

# Timebox Range + Drivers
10–20 minutes per batch depending on errors

# Failure Modes
- QA skipped
- Reviewer inconsistency
- Errors not logged
- Feedback unclear
- Rework not verified

# Escalation Rules
Stop work if high-severity errors exceed threshold

# Assumption Ledger
- Reviewer understands labels
- Sampling is sufficient

# Step-by-Step Procedure

1. Select sample images from completed jobs  
   Expected result: Sample ready for review

2. Review annotations against label spec  
   Expected result: Errors identified

3. Log issues in QA report  
   Expected result: Issues documented

4. Decide severity  
   Expected result: Clear prioritization

5. Trigger rework if needed  
   Expected result: Quality corrected

# Embedded Quality Checks
- Sampling rate followed
- Errors categorized
- Rework verified

# Artifacts Produced
- TPL_QA_Report_v0.1.md

# Example Run
Reviewed 10 images, found 1 low-severity issue

# Failure Case
Repeated high errors → stop batch and retrain annotator