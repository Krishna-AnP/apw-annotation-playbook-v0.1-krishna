# SOP – Initiation: Tool Setup (CVAT)

# Purpose
To initialize CVAT for a new annotation job.

# Scope
In: Tool access, project readiness  
Out: Annotation execution

# Owner Role
Annotation Engineer

# Inputs Needed
- CVAT login credentials
- Dataset images

# Outputs Produced
- CVAT project
- CVAT task

# Tools Touched
- CVAT Cloud
- Web Browser

# Timebox Range
15–30 minutes  
Drivers: dataset size, network stability

# Failure Modes (Top 5)
1. Project not created
2. Label save failure
3. Image upload failure
4. Permission issues
5. Browser crash

# Escalation Rules
Stop-the-line if project is not visible after creation.

# Assumption Ledger
- CVAT server is accessible
- Dataset is image-only

# Step-by-Step Procedure
1. Login to CVAT  
   Expected Result: Dashboard loads

2. Navigate to Projects → Create Project  
   Expected Result: New project visible

3. Save project name `Parcel-Boxes-30`  
   Expected Result: Project saved

4. Proceed to task creation  
   Expected Result: Task creation screen opens

# Embedded Quality Checks
- Project name matches spec
- No duplicate projects created

# Artifacts Produced
- CVAT Project ID
- Task ID

# Example Run (10 Items)
Project created and task initiated with 10 images.

## Failure Case Walkthrough
Project creation failed → retried with admin assistance → success.
