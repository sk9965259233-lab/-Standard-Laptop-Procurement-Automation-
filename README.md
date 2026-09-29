# Standard Laptop Procurement Automation

## Project Overview
This ServiceNow project automates the IT hardware procurement workflow for a Standard Laptop request.

When a Standard Laptop request is approved, Flow Designer automatically creates a Catalog Task and assigns it to the Hardware team for laptop configuration.

## Objectives
- Automate Catalog Task creation after approval
- Assign the task to the Hardware team
- Reduce manual task creation
- Improve visibility and processing speed
- Provide a consistent procurement workflow

## ServiceNow Components
- Service Catalog
- Requested Items
- Approvals
- Flow Designer
- Catalog Tasks
- Hardware assignment group

## Workflow
1. User submits a Standard Laptop request.
2. The request enters the approval process.
3. When the request is approved, the Flow is triggered.
4. A Catalog Task is created.
5. The task is assigned to the Hardware team.
6. The Hardware team configures the laptop and completes the task.

## Expected Result
An approved Standard Laptop request automatically produces a Catalog Task assigned to the Hardware team without requiring manual task creation.

> Note: The actual ServiceNow application configuration is performed inside the ServiceNow instance. This repository contains the project documentation and implementation reference.
