# SOP – Initiation – CVAT Cloud (v0.1)

# Purpose
To set up and execute a toy image annotation project using CVAT Cloud.

# Scope
In scope:  
- CVAT Cloud account setup  
- Project and task creation  
- Image upload and annotation  
- Export of annotation results  

# Owner role
Annotation Project Operator (Intern)

# Inputs needed
- CVAT Cloud account (https://app.cvat.ai)
- Sample image dataset (10 images {toys,games,etc}, JPG/PNG)
- Internet access
- Web browser (Chrome)

# Outputs produced
- CVAT project
- CVAT task with one job
- Annotated images
- Exported annotation ZIP file

# Tools touched
- CVAT Cloud (web-based annotation tool)

# Timebox range + drivers
Estimated time: 45-60 minutes  
Drivers affecting time:
- Number of images
- Image size
- Familiarity with CVAT interface

# Failure modes (top 5)
1. CVAT Cloud login failure
2. Incorrect label configuration
3. Images not uploaded correctly
4. Annotations not saved
5. Export failure or wrong format selection
(got no failures)

# Escalation rules (stop-the-line)
- Stop if CVAT Cloud is inaccessible
- Stop if images fail to upload after retry
- Stop if annotation export fails repeatedly

# Assumption ledger
- CVAT Cloud is used instead of local CVAT due to Docker/WSL instability on Windows
- A toy dataset of 10 images is sufficient for SOP validation
- Single-user annotation flow is acceptable

# Step-by-step procedure
Step 1: Log in to CVAT Cloud
- Open https://app.cvat.ai
- Log in using registered credentials  
Expected result: CVAT dashboard is visible

Step 2: Create a new project
- Click Projects → Create Project
- Enter project name and submit  
Expected result: New project is created successfully

Step 3: Define labels
- Open project settings
- Add required labels (e.g., `car`, `person`)  
Expected result: Labels are saved and available for tasks

Step 4: Create a task
- Click Tasks → Create Task
- Enter task name and select the project  
Expected result: Task creation screen opens

Step 5: Upload images
- Select My Computer (any folder)
- Upload 10 image files (dummy data)
- Click Submit & Open  
Expected result: Job is created with uploaded images

Step 6: Annotate images
- Open the job
- Draw bounding boxes using defined labels
- Save annotations regularly  
Expected result: All images are annotated

Step 7: Complete the job
- Mark job state as Completed  
Expected result: Job status reflects completion

Step 8: Export annotations
- Go to task actions
- Select export format (CVAT for images / COCO)
- Download ZIP file  
Expected result: Annotation ZIP file is downloaded

# Embedded quality checks
- Ensure all images have at least one annotation where applicable
- Verify correct label usage
- Confirm annotations are saved before export
- Validate exported ZIP file contains annotation data

# Artifacts produced
- `EVID/cvat_cloud_day1/export_toy-task-10-images_cvat.zip`
- Screenshots stored in `EVID/cvat_cloud_day1/`

# Example run on 10 items
- Project created with 10 sample images
- One label (`car`) defined and Second label (`person`) defined
- All 10 images annotated
- Annotations successfully exported

# Failure-case walkthrough
Issue: Local CVAT installation failed due to Docker/WSL `unexpected EOF` errors on Windows  
Detection: Repeated Docker image pull failures  
Action taken: Switched to CVAT Cloud to unblock execution  
Outcome: Annotation project completed successfully using cloud setup