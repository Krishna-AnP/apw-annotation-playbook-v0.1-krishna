# SOP: Day 1 – Project Setup and Annotation Execution

# Objective
To set up the annotation project and perform bounding-box annotations on the Parcel Dataset (Toy) as per client guidelines.

# Scope
This SOP covers:
- Project understanding
- Label definition
- Annotation execution
- Initial validation

# Dataset Overview
- Total Images: 30
- Domain: Warehouse parcel images
- Annotation Type: Bounding boxes

# Label Definitions
1. package – Outer parcel box visible in the image.
2. label – Shipping label or sticker pasted on the parcel.
3. barcode – Barcode region consisting of vertical black lines on white background.

# Annotation Rules
- Draw tight bounding boxes.
- Annotate only visible regions.
- Do not guess occluded or hidden areas.
- Ignore gray occluder rectangles.
- Multiple instances per image are allowed.

# Tool Setup
- Annotation tool: CVAT
- Export format planned: COCO JSON and (YOLO or CSV)

# Annotation Process
1. Load dataset into the project.
2. Create labels as per client brief.
3. Annotate each image carefully following rules.
4. Perform self-review after every image.

# Output
- Fully annotated dataset for Day 1 images.
- Annotations saved within the tool for export.

# Responsibility
- Annotator: Krishna
