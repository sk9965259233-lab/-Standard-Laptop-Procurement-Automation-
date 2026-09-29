# Flow Designer Design

## Trigger
A Standard Laptop catalog request reaches the required approved state.

## Actions
1. Identify the approved Requested Item.
2. Create a Catalog Task.
3. Set the task short description to indicate laptop configuration.
4. Assign the task to the Hardware assignment group.
5. Map relevant request information to the task.
6. Save and activate the Flow.

## Example Task
**Short description:** Configure Standard Laptop

**Assignment group:** Hardware

**Source:** Approved Standard Laptop Requested Item

## Validation
Test the flow using a Standard Laptop request and confirm:
- Approval completes successfully.
- A Catalog Task is created automatically.
- The task is assigned to the Hardware team.
- Request details are available on the task.
