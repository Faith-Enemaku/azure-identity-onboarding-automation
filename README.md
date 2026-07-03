# Automated User Onboarding and Identity Protection in Microsoft Azure

## Project Overview

This project automates user onboarding in Microsoft Entra ID (Azure Active Directory) using Python and the Microsoft Graph API. The solution validates user data, creates user accounts, assigns users to security groups, and applies identity management best practices to improve efficiency and security.

## Objectives

- Automate user onboarding from a CSV file
- Validate and clean user data before provisioning
- Create users in Microsoft Entra ID
- Assign users to security groups
- Reduce manual errors and improve onboarding efficiency

## Technologies Used

- Microsoft Azure (Entra ID)
- Microsoft Graph API
- Python
- Pandas
- Git and GitHub

## 📁 Project Structure

This project is organized following an enterprise-style structure to separate automation logic, documentation, and operational procedures.

```text
docs/          → Architecture, security, and identity documentation  
runbooks/      → Step-by-step operational procedures and troubleshooting guides  
scripts/       → Python automation scripts for user onboarding and validation  
diagrams/      → Azure architecture and workflow diagrams  
screenshots/   → Execution evidence and validation outputs  
```

### Why this structure matters

- Improves maintainability of automation scripts
- Separates documentation from code
- Supports enterprise-level governance and auditing
- Makes the project easier to understand for reviewers and recruiters

## Workflow

1. Administrator prepares a CSV file containing user information.
2. The Python automation script imports the CSV data.
3. User records are validated for required fields, email format, and duplicates.
4. Microsoft Graph API provisions users in Microsoft Entra ID.
5. Users are assigned to the appropriate security groups.
6. Execution results are logged for auditing and troubleshooting purposes.

## Architecture

### System Flow

```text
CSV File
    │
    ▼
Python Automation Script
    │
    ▼
Data Validation
    │
    ▼
Microsoft Graph API
    │
    ▼
Microsoft Entra ID
    │
    ▼
Security Group Assignment
    │
    ▼
Execution Log
```

### Architecture Diagram

The architecture diagram is located in the `diagrams` folder.
