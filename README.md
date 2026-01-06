# APW Annotation Playbook – CVAT Cloud (v0.1)

# Overview
This repository contains a complete, step-by-step "Annotation Delivery Playbook" built as part of the APW internship task.  
The objective is to define a repeatable, reliable operating system for running data annotation projects end-to-end, covering initiation, planning, execution, monitoring, and closure.
The playbook is designed so that a new intern can run a small annotation project independently without constant supervision.

# Tool Used
- CVAT Cloud (https://app.cvat.ai/)
- Sample / toy image dataset only (10 images)
- No real client data used

# Repository Structure
├── README.md
├── SOP/ # Standard Operating Procedures (how to run the work)
├── TPL/ # Templates (reusable documents to fill)
├── CHK/ # Checklists (quality gates / stop-the-line checks)
└── EVID/ # Evidence (screenshots, exports proving execution)

# Day-wise Work Summary

# Day 1 – Initiation (Setup & First Run)
# Objective 
Validate that a complete annotation project can be executed end-to-end using the selected tool.

# Work Performed
- Explored CVAT setup; shifted to CVAT Cloud due to local setup limitations
- Created a CVAT Cloud project and task
- Uploaded 10 sample images
- Defined labels
- Completed annotation for all images
- Exported annotation results
- Captured screenshots as execution proof

# Documents Created
- SOP: CVAT Cloud Initiation
- Template: Label Specification
- Checklist: Project Intake Gate
- README (Day 1 update)

# Evidence
- Screenshots of project, task, annotation UI, export
- Exported annotation ZIP file  
Stored under:
EVID/cvat_cloud_day1/

# Outcome
 Tool validated  
 Annotation workflow executed  
 Export generated  

# Day 2 – Planning (Clarity & Readiness)

# Objective
Ensure annotation can be performed consistently and correctly by removing ambiguity before scale.

# Focus Areas
- Label clarity
- Edge case handling
- Annotator training readiness
- Batch planning

# SOPs Created
- Label Specification Workflow
- Edge Case Handling
- Annotator Training & Readiness

# Templates Created
- Label Specification
- Edge Case Library
- Training Quiz
- Batch Plan

# Checklist
- Spec Readiness Gate

# Outcome
 Labels finalized and frozen  
 Edge cases documented  
 Annotator readiness ensured  

# Day 3 – Execution (Annotation, Review & Rework)

# Objective
Define how annotation work is executed daily, reviewed, and corrected.

# SOPs Created
- Batch Release SOP
- Annotation Workflow SOP
- Review & Rework Loop SOP

# Templates Created
- Daily Production Report
- QA Report

# Checklist
- Batch Release Gate

# Outcome
 Disciplined execution flow defined  
 Review and rework loop established  
 Daily tracking enabled  

# Day 4 – Monitoring & Control (Quality & Metrics)

# Objective
Monitor quality and progress continuously and manage changes safely.

# SOPs Created
- QA Checks SOP
- Metrics Tracking SOP
- Change Handling SOP

# Templates Created
- QA Metrics
- Change Request
- Client Status Update

# Checklist
- Delivery Readiness Gate

### Outcome
 Quality monitored continuously  
 Metrics tracked for progress and errors  
 Controlled change management in place  

# Day 5 – Closure (Delivery & Learning)

# Objective
Package final outputs, obtain sign-off, and close the project cleanly.

# SOPs Created
- Delivery Packaging SOP
- Project Closure SOP

# Templates Created
- Acceptance Signoff
- Retrospective / Postmortem

# Checklist
- Closure Gate

# Outcome
 Final delivery packaged  
 Acceptance signoff defined  
 Project closed with learnings documented  

# Evidence Summary
All execution proof, including screenshots and exports, is stored under:
EVID/
├── cvat_cloud_day1/
├── cvat_cloud_day2/
├── cvat_cloud_day3/
├── cvat_cloud_day4/
└── cvat_cloud_day5/

# Key Takeaway
This repository represents a complete annotation delivery operating system, not just a one-time annotation task.  
It ensures:
- Repeatability
- Quality control
- Scalability
- Clean delivery and closure

# Status
 Day 1 – Initiation  
 Day 2 – Planning  
 Day 3 – Execution  
 Day 4 – Monitoring & Control  
 Day 5 – Closure  

Playbook Version: v0.1  
Status: Complete


---

# CVAT Annotation Execution – Parcel Dataset (Toy)

# Project
Parcel-Boxes-30

# Branch
`stress-test-06jan`

# Tool
CVAT Cloud

# Day 1 – Setup & Calibration (06 Jan 2026)

- Created `stress-test-06jan` branch for execution.
- As per reviewer guidance, an existing toy CVAT project was overridden to create the project Parcel-Boxes-30.
- Labels configured:
  - package
  - label
  - barcode  
  (bounding boxes)
- Single task created and all 30 images uploaded.
- Calibration annotation completed on exactly 10 images.

# Calibration Metrics
- Start Time: 06:09 PM IST  
- End Time: 06:33 PM IST  
- Images Annotated: 10  
- Avg Objects per Image: 3–5  

# Observations / Edge Cases
- Parcels partially outside image boundaries.
- Labels and barcodes partially occluded by gray rectangles.
- Multiple packages and multiple labels present in some images.

# Assumptions
- Only visible regions were annotated; no hidden parts inferred.
- Gray occluder rectangles were ignored as per client brief.
- Single-annotator workflow assumed for estimation.

# Day 2 – Completion, QA & Delivery (07 Jan 2026)

- Completed annotation for remaining 20 images.
- Conducted QA audit on 6 randomly sampled images (20%).
- Identified minor defects related to loose bounding boxes and missing barcode regions.
- All identified defects were corrected and revalidated.
- Generated final exports and packaged delivery artifacts.

# QA Summary
- Total Images Audited: 6
- Defect Types:
  - Loose bounding boxes
  - Missing barcode annotation
- Severity: Minor
- Final QA Status: PASS

# Deliverables (Final – 07 Jan 2026)

- Total Images Annotated: 30
- Object Classes:
  - package
  - label
  - barcode

# Annotation Formats Delivered
- COCO JSON (primary)
- YOLO (additional)

# Dataset Exports
- COCO JSON export for training and validation
- YOLO export provided as an additional format
