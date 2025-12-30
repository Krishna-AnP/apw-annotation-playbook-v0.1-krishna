# SOP – Batch Release (v0.1)

# Purpose
Define how annotation batches are released for execution.

# Scope
In: Batch preparation and release  

# Owner Role
Project Operator

# Inputs Needed
- Approved Label Specification
- Completed Training Checklist
- Batch Plan

# Outputs Produced
- Released annotation batch
- Assigned annotator

# Tools Touched
- CVAT Cloud
- GitHub documentation

# Timebox Range + Drivers
- 10–20 minutes per batch  
- Depends on batch size

# Failure Modes (Top 5)
1. Batch released without approval  
2. Wrong data included  
3. Annotator not trained  
4. Labels not frozen  
5. Missing batch documentation  

# Escalation Rules
- Stop batch release if any checklist fails
- Escalate to project owner

# Assumption Ledger
- Annotators are available
- Batch plan is approved

# Step-by-Step Procedure

1. Verify label specification is frozen  
   Expected result: No label changes pending

2. Verify annotator training status  
   Expected result: Annotator is certified

3. Confirm batch details from batch plan  
   Expected result: Correct data scope

4. Release batch in CVAT  
   Expected result: Job assigned to annotator

5. Notify annotator  
   Expected result: Work starts without confusion

# Embedded Quality Checks
- Batch release checklist completed
- Annotator acknowledged assignment

# Artifacts Produced
- TPL_Batch_Plan_v0.1.md

# Example Run (Toy Project)
- Batch of 10 images released
- Assigned to one annotator
- Annotation started successfully

# Failure Case Walkthrough
Issue: Batch released before training  
Detection: Checklist failure  
Action: Roll back batch release  
Outcome: Batch released only after training
