# SOP – Edge Case Handling (v0.1)

# Purpose
Define how edge cases are identified, documented, and resolved during annotation planning.

# Scope
In: Identification and handling of ambiguous cases  

# Owner Role
Project Operator / QA Lead

# Inputs Needed
- Sample images
- Label specification document
- Annotator feedback

# Outputs Produced
- Updated Edge Case Library
- Clarified annotation rules

# Tools Touched
- CVAT Cloud
- GitHub documentation

# Timebox Range + Drivers
- 20–40 minutes  
- Depends on number of ambiguous cases

# Failure Modes (Top 5)
1. Annotators guess instead of reporting issues  
2. Edge cases not documented  
3. Conflicting instructions  
4. Late discovery of ambiguity  
5. Rework due to inconsistent labeling  

# Escalation Rules
- Pause annotation if repeated confusion occurs
- Escalate to project owner for clarification

# Assumption Ledger
- Annotators will flag unclear cases
- Edge cases are manageable in number

# Step-by-Step Procedure

1. Annotator identifies a confusing case  
   Expected result: Edge case noticed early

2. Annotator pauses annotation for that item  
   Expected result: No incorrect labeling

3. Annotator documents the issue  
   Expected result: Edge case recorded clearly

4. Project operator reviews the case  
   Expected result: Correct resolution decided

5. Resolution added to Edge Case Library  
   Expected result: Future confusion avoided

6. Annotators informed of the resolution  
   Expected result: Consistent labeling resumes

# Embedded Quality Checks
- Edge case library updated
- Resolution is clear and actionable
- Annotators acknowledge the update

# Artifacts Produced
- TPL_EdgeCase_Library_v0.1.md

# Example Run (Toy Project)
- Found partially visible object
- Added rule to label visible portion only
- Annotators followed updated rule

# Failure Case Walkthrough
Issue: Annotator unsure about blurred object  
Detection: Question raised during annotation  
Action: Rule added to Edge Case Library  
Outcome: Annotation resumed without guessing