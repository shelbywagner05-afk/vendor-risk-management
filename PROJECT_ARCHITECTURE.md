# Vendor Risk Management Application Architecture

## Technology Stack

- Django (Python)
- SQLite Database
- Bootstrap 5
- Chart.js
- GitHub for Version Control

## Core Features

- User Authentication
- Vendor Management
- Vendor Risk Assessments
- Risk Scoring
- Risk Reporting
- Dashboard Metrics

## Database Entities

### Vendor
- Name
- Category
- Contact Information
- Criticality Level
- Data Access Level

### Assessment
- Vendor
- Assessor
- Risk Score
- Risk Level
- Assessment Date

### Question
- Question Text
- Category
- Weight

### Response
- Assessment
- Question
- Selected Answer

## Risk Scoring

Low Risk: 0-33

Medium Risk: 34-66

High Risk: 67-100

## Application Pages

1. Login
2. Dashboard
3. Vendor List
4. Add/Edit Vendor
5. Vendor Details
6. Risk Assessment
7. Assessment Results
8. Reports

## Development Roadmap

Phase 1:
- Authentication
- Vendor Management

Phase 2:
- Assessment Workflow

Phase 3:
- Risk Scoring

Phase 4:
- Dashboard and Reporting

Phase 5:
- Testing and Deployment
