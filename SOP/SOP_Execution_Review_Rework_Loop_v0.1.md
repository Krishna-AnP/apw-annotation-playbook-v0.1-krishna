# SOP – Review & Rework Loop (v0.1)

# Purpose
Define how completed annotations are reviewed and corrected before final acceptance.

# Scope
In: Review and rework of annotations  

# Owner Role
Reviewer / QA Operator

# Inputs Needed
- Completed annotation job
- Label specification
- Edge Case Library

# Outputs Produced
- Approved annotations
- QA feedback
- Reworked annotations (if needed)

# Tools Touched
- CVAT Cloud
- GitHub documentation

# Timebox Range + Drivers
- 10–30 minutes per batch  
- Depends on number of errors found

# Failure Modes (Top 5)
1. Review skipped completely  
2. Reviewer misses errors  
3. Feedback not clear  
4. Annotator ignores feedback  
5. Rework not verified  

# Escalation Rules
- Stop delivery if major errors found
- Escalate repeated issues to project owner

# Assumption Ledger
- Reviewer understands label rules
- Annotator responds to feedback

# Step-by-Step Procedure

1. Reviewer opens completed job  
   Expected result: All images accessible

2. Reviewer checks random samples  
   Expected result: Quality level understood

3. Reviewer logs issues  
   Expected result: Errors clearly documented

4. If issues found, mark job for rework  
   Expected result: Annotator notified

5. Annotator fixes issues  
   Expected result: Errors corrected

6. Reviewer re-checks updated job  
   Expected result: Quality meets standard

7. Approve job  
   Expected result: Job ready for delivery

# Embedded Quality Checks
- Sample review completed
- Errors documented
- Rework verified

# Artifacts Produced
- TPL_QA_Report_v0.1.md

# Example Run (Toy Project)
- Reviewed 10 annotated images
- Found 1 loose bounding box
- Rework requested and fixed
- Job approved

# Failure Case Walkthrough
Issue: Multiple incorrect labels  
Detection: Review sampling  
Action: Full rework requested  
Outcome: Job approved after correction
