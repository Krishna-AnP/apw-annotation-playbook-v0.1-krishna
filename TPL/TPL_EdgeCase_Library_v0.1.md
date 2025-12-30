# Template – Edge Case Library (v0.1)

# How to Use This Template
Use this document to record confusing or ambiguous cases found during annotation.
Annotators must follow the listed resolution rules.

# Project Information
- Project Name: ________________________ (Required)
- Task Name: ________________________ (Required)
- Tool Used: CVAT Cloud (Required)

# Edge Case Table

| Edge Case ID | Description of the Issue | How to Handle It | Example Image Ref |
|-------------|--------------------------|------------------|-------------------|
| EC-01 | Object partially visible | Draw bounding box around visible part | image_03.jpg |
| EC-02 | Object blurred | Label only if shape is recognizable | image_07.jpg |
| EC-03 | Multiple objects overlapping | Draw separate boxes if separable | image_09.jpg |

# Validation Rules
This template is invalid if:
- Edge cases are not documented
- Resolution instructions are missing
- Table is left empty

# Sample Filled Example (Toy Project)

- Project Name: toy-image-annotation-v0  
- Task Name: toy-task-10-images  

| Edge Case ID | Description of the Issue | How to Handle It | Example Image Ref |
|-------------|--------------------------|------------------|-------------------|
| EC-01 | Ball partially outside frame | Label visible portion only | img_02.jpg |
| EC-02 | Ball slightly blurred | Label if boundary visible | img_06.jpg |