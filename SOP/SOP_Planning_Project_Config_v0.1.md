# SOP – Planning: Project Configuration

# Purpose
To configure CVAT project and labels as per client brief.

# Scope
In: Client brief, label rules  
Out: Ready-to-annotate project

# Owner Role
Annotation Engineer

# Inputs Needed
- Client label definitions
- Dataset

# Outputs Produced
- Configured labels
- Active annotation task

# Tools Touched
- CVAT Cloud

# Timebox Range
20–40 minutes  
Drivers: number of labels, dataset size

# Failure Modes
1. Incorrect label names
2. Missing labels
3. Extra unused labels
4. Wrong task assignment
5. Dataset mismatch

# Escalation Rules
Stop if labels do not match client brief.

# Assumption Ledger
- Labels are bounding-box type
- Occlusions may exist

# Step-by-Step Procedure
1. Open project `Parcel-Boxes-30`  
   **Expected Result:** Project dashboard visible

2. Create labels:
   - package
   - label
   - barcode  
   Expected Result: Labels saved correctly

3. Review client rules before annotation  
   Expected Result: Annotator aligned on rules

4. Upload dataset images  
   Expected Result: All images visible in task

# Embedded Quality Checks
- Label names exactly match client brief
- Image count verified

# Artifacts Produced
- Label configuration
- Task with images

# Example Run (10 Items)
Labels created and 10 images uploaded successfully.
## Failure Case Walkthrough
Label typo detected → deleted → recreated correctly.
