# Template – Annotator Training Quiz (v0.1)

# How to Use This Template
Use this quiz to verify that annotators understand label rules and edge cases
before starting annotation work.

# Project Information
- Project Name: ________________________ (Required)
- Task Name: ________________________ (Required)
- Tool Used: CVAT Cloud (Required)
- Annotator Name: ________________________ (Required)

# Quiz Instructions
- Answer all questions
- Refer to Label Specification and Edge Case Library
- Minimum passing score: 80%

# Quiz Questions

Q1. When should the main label be applied?  
☐ Always  
☐ Only when the object is clearly visible  
☐ Only when the object is centered  

Q2. How should a partially visible object be labeled? 
☐ Do not label it  
☐ Label only the visible portion  
☐ Guess the full shape  

Q3. What should you do if an image is unclear or confusing?  
☐ Guess the label  
☐ Skip the image  
☐ Pause and report as an edge case  

Q4. Should labels be changed during annotation? 
☐ Yes, anytime  
☐ Only by annotator  
☐ No, labels must be frozen  

Q5. Where are edge cases documented?  
☐ In personal notes  
☐ In Edge Case Library  
☐ Not required  

# Validation Rules
This quiz is invalid if:
- Any question is unanswered
- Annotator has not reviewed label spec
- Score is below passing threshold

# Sample Filled Example

- Project Name: toy-image-annotation-v0  
- Task Name: toy-task-10-images  
- Annotator Name: Test Annotator  

Sample Answers: 
Q1: Only when the object is clearly visible  
Q2: Label only the visible portion  
Q3: Pause and report as an edge case  
Q4: No, labels must be frozen  
Q5: In Edge Case Library  

Result: Pass