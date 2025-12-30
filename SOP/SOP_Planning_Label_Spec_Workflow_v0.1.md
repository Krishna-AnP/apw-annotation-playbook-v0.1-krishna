# SOP – Label Specification Workflow (v0.1)

# Purpose
Define how label specifications are created, reviewed, and finalized before annotation starts.

# Scope
In: Label definition, review, approval  

# Owner Role
Project Operator / Annotation Lead

# Inputs Needed
- Sample dataset (images)
- Project requirements
- Annotation tool access (CVAT Cloud)

# Outputs Produced
- Approved Label Specification document
- Final list of labels for the project

# Tools Touched
- CVAT Cloud
- GitHub (documentation)

# Timebox Range + Drivers
- 30–60 minutes  
- Faster if dataset is simple  
- Slower if objects are ambiguous

# Failure Modes (Top 5)
1. Labels are unclear  
2. Different people interpret labels differently  
3. Missing edge cases  
4. Too many unnecessary labels  
5. Labels changed after annotation starts  

# Escalation Rules
- Pause work if labels are unclear  
- Escalate to project owner before annotation begins

# Assumption Ledger
- Dataset contains visible and distinguishable objects  
- Annotation type is bounding box

# Step-by-Step Procedure

1. Review 5–10 sample images  
   Expected result: Understand what objects need labeling

2. Decide label names  
   Expected result: Short, clear label names

3. Write label descriptions  
   Expected result: Clear definition for each label

4. Define when to use and when not to use labels  
   Expected result: Reduced confusion during annotation

5. Document basic edge cases  
   Expected result: Common doubts answered upfront

6. Review label spec once  
   Expected result: Errors or ambiguity removed

7. Freeze label specification  
   Expected result: No changes during annotation

# Embedded Quality Checks
- Each label has a description
- Each label has usage rules
- Edge cases are documented

# Artifacts Produced
- TPL_Label_Spec_v0.1.md

# Example Run (Toy Project)
- Reviewed 10 images
- Defined one label: object
- Added usage rules
- Finalized label spec before task creation

# Failure Case Walkthrough
Issue: Label meaning unclear  
Detection: Annotator confusion  
Action: Pause annotation → update label spec → resume work