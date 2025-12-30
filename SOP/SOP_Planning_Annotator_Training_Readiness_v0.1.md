# SOP – Annotator Training & Readiness (v0.1)

# Purpose
Ensure annotators are properly trained and ready before starting annotation work.

# Scope
In: Annotator training, readiness checks  

# Owner Role
Project Operator / QA Lead

# Inputs Needed
- Label Specification document
- Edge Case Library
- Training Quiz

# Outputs Produced
- Trained and approved annotators
- Reduced annotation errors

# Tools Touched
- CVAT Cloud
- GitHub documentation

# Timebox Range + Drivers
- 15–30 minutes per annotator  
- Depends on complexity of label rules

# Failure Modes (Top 5)
1. Annotator starts without training  
2. Quiz not completed  
3. Misunderstanding of labels  
4. Ignoring edge cases  
5. Inconsistent annotations  

# Escalation Rules
- Stop annotation if quiz is not passed
- Escalate to project owner if confusion persists

# Assumption Ledger
- Annotators review all documents before starting
- Quiz accurately reflects label understanding

# Step-by-Step Procedure

1. Share Label Specification with annotator  
   Expected result: Annotator understands label definitions

2. Share Edge Case Library  
   Expected result: Annotator aware of common ambiguities

3. Ask annotator to complete Training Quiz  
   Expected result: Quiz completed with required score

4. Review quiz results  
   Expected result: Readiness confirmed

5. Approve annotator for work  
   Expected result: Annotator allowed to start annotation

# Embedded Quality Checks
- Quiz score ≥ passing threshold
- No unresolved questions
- Annotator acknowledgment received

# Artifacts Produced
- TPL_Training_Quiz_v0.1.md
- Completed quiz records

# Example Run (Toy Project)
- Annotator reviewed label spec
- Passed quiz with full score
- Approved to annotate 10 images

# Failure Case Walkthrough
Issue: Annotator fails quiz  
Detection: Low quiz score  
Action: Re-train annotator and re-test  
Outcome: Annotator approved only after passing