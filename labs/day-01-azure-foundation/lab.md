# Day 1 Lab: Azure Foundation

## Objective
Set up the foundation for AZ-104 practice by creating a resource group, applying tags, and documenting the environment.

## Skills Practiced
- Azure Portal navigation
- Resource groups
- Tags
- Basic governance
- Azure CLI basics

## Tasks

### Task 1: Sign in to Azure
Go to https://portal.azure.com

### Task 2: Create a Resource Group
Create a resource group named:

az104-rg-day01

Recommended region:

East US or your preferred region

### Task 3: Add Tags
Add these tags:

Environment = Study  
Owner = YourName  
Course = AZ-104  
Day = 01  

### Task 4: Verify in Azure CLI
Run:

az group show --name az104-rg-day01

### Task 5: Screenshot
Save screenshots of:
- Resource group overview
- Tags page
- CLI output

Put screenshots in:

labs/day-01-azure-foundation/screenshots/

## Reflection Questions
1. What is a resource group?
2. Why are tags important?
3. What happens if you delete a resource group?
4. How can tags help with cost management?

## Cleanup
Do not delete the resource group yet. We will reuse it.
