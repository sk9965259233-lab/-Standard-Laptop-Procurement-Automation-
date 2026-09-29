# ServiceNow Setup Guide

## 1. Service Catalog
Create or use a catalog item named **Standard Laptop**.

## 2. Approval
Configure the request so that approval is required before hardware processing.

## 3. Flow Designer
Create a flow named:

**Standard Laptop Procurement Automation**

Configure the flow to run after the Standard Laptop request is approved.

## 4. Catalog Task
Add an action to create a Catalog Task.

Suggested values:
- Short description: `Configure Standard Laptop`
- Assignment group: `Hardware`

## 5. Test
Submit a Standard Laptop request, approve it, and verify that the Catalog Task is automatically created and assigned.

## 6. Activate
After successful testing, activate the flow.
