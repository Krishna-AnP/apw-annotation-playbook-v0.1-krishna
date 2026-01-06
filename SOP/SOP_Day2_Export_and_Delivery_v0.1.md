# SOP: Day 2 – Export, QA, and Delivery

# Objective
To complete annotation exports, perform final QA, and prepare delivery artifacts.

# Scope
- Exporting annotations
- Verifying output formats
- Packaging delivery

# Export Details
- Primary Format: COCO JSON
- Secondary Format: CSV

# Export Process
1. Validate annotations inside the tool.
2. Export dataset in COCO JSON format.
3. Convert/export annotations to CSV.
4. Verify file integrity and label mapping.

# Folder Structure
- annotations/
- images/
- exports/
  - Parcel-Dataset-Toy_COCO.json
  - Parcel-Dataset-Toy_annotations.csv

# Validation Checks
- File opens without errors
- All 30 images present
- Category IDs match labels

# Responsibility
- Annotator & QA: Krishna
