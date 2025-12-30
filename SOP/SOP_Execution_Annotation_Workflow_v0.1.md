# SOP – Annotation Workflow (v0.1)

# Purpose
Define the standard steps annotators must follow while performing annotation work.

# Scope
In: Image annotation  

# Owner Role
Annotator

# Inputs Needed
- Released batch
- Approved label specification
- Access to CVAT Cloud

# Outputs Produced
- Annotated images
- Completed job status

# Tools Touched
- CVAT Cloud

# Timebox Range + Drivers
- Depends on number of images  
- Slower if images are complex

# Failure Modes (Top 5)
1. Annotator forgets to save work  
2. Wrong label used  
3. Images skipped unintentionally  
4. Guessing on edge cases  
5. Incomplete annotations  

# Escalation Rules
- Stop annotation if label confusion occurs
- Report edge cases immediately

# Assumption Ledger
- Annotator is trained and certified
- Label spec is available during work

# Step-by-Step Procedure

1. Open assigned job in CVAT  
   Expected result: Correct images visible

2. Select correct label  
   Expected result: Label rules followed

3. Draw bounding boxes carefully  
   Expected result: Objects fully covered

4. Save annotations regularly  
   Expected result: No work lost

5. Review image before moving next  
   Expected result: No missed objects

6. Repeat for all images  
   Expected result: Job completed fully

7. Mark job as completed  
   Expected result: Ready for review

# Embedded Quality Checks
- All images annotated
- Correct labels used
- Job marked completed

# Artifacts Produced
- CVAT job with annotations

# Example Run (Toy Project)
- Annotated 10 images
- Saved work regularly
- Job completed without errors

# Failure Case Walkthrough
Issue: Annotator unsure about object  
Detection: Confusion during annotation  
Action: Pause and report edge case  
Outcome: Correct rule applied
