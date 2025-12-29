# Template – Label Specification (v0.1)

# How to Use This Template
Fill this document before annotation starts.  
All annotators and reviewers must read and agree on this specification.

# Project Information
- Project Name: ___________________________ (Required)
- Task Name: ___________________________ (Required)
- Tool Used: CVAT Cloud  (Required)
- Annotation Type: Bounding Box  (Required) 

# Label Definitions
# Label 1
- Label Name: ___________________________  (Required)
- Description:
  Clear definition of what this label represents.
- Annotation Shape: Rectangle
- When to Use:
  Describe when this label should be applied.
- When NOT to Use: 
  Describe cases where this label should not be applied.

# Annotation Guidelines
- Bounding boxes should tightly cover the object
- Do not include excessive background
- One object = one bounding box
- Partial objects should still be labeled if clearly visible

# Edge Cases
List tricky or ambiguous cases and how to handle them.

| Edge Case | How to Label |
|----------|--------------|
| Example: Partial object | Draw bounding box around visible portion |
| Example: Occluded object | Label only if >50% visible |

# Quality Rules (Validation)
This label spec is considered invalid if:
- Label names are missing
- Descriptions are unclear or ambiguous
- Edge cases are not documented

# Sample Filled Example (Toy Project)
- Project Name: toy-image-annotation-v0  
- Task Name: toy-task-10-images  
- Tool Used: CVAT Cloud  
- Annotation Type: Bounding Box  

# Label 1
- Label Name: car  
- Description: Any visible passenger vehicle such as sedan, hatchback, or SUV.
- Annotation Shape: Rectangle
- When to Use:  
  Apply when a car is clearly visible in the image.
- When NOT to Use:
  Do not apply to trucks, buses, or bikes.

# Edge Case Example
| Edge Case | How to Label |
|----------|--------------|
| Car partially visible | Draw bounding box around visible area |
