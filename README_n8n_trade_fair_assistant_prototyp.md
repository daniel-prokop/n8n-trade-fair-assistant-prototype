# n8n-Trade-Fair-Assistant-Prototype

An AI-powered lead qualification and follow-up workflow built with n8n.

The workflow transforms unstructured trade fair conversation notes into enriched sales opportunities by combining AI extraction, company research, lead scoring, CRM logging and automated report generation.

---

## Overview

Many trade fair leads are documented inconsistently, making follow-up activities difficult and time-consuming.

This prototype automates the process by:

- Extracting lead information from conversation notes
- Enriching leads with public company research
- Calculating an opportunity score
- Generating management-ready reports
- Logging lead data into Google Sheets
- Creating personalized follow-up email drafts

---

## Workflow

![Workflow Overview](screenshots/workflow-overview.png)

### Process Flow

1. Capture trade fair conversation notes
2. Extract lead details using AI
3. Research company information using public sources
4. Consolidate lead and company data
5. Calculate lead score and qualification
6. Generate a management report
7. Store lead information in Google Sheets
8. Create a personalized follow-up email draft

---

## Features

### AI Lead Extraction

Automatically identifies:

- Contact information
- Company details
- Training needs
- Pain points
- Budget indicators
- Timeline indicators
- Follow-up requests

### Company Research

Retrieves publicly available information such as:

- Company description
- Headquarters
- Employee count
- Products and services
- Geographic presence
- Relevant public information

### Lead Scoring

Lead qualification based on:

| Factor | Weight |
|----------|----------|
| Training Need | 20 |
| Budget | 25 |
| Timeline | 20 |
| Company Size / Scope | 20 |
| Engagement / Next Step | 15 |

Lead Categories:

- Hot: 75-100
- Warm: 50-74
- Cold: 0-49

### Automated Reporting

Generates a structured management report including:

- Opportunity summary
- Lead score
- Company background
- Recommended next actions
- Supporting sources

### CRM Logging

Stores qualified lead information in Google Sheets for tracking and follow-up management.

### Follow-Up Drafting

Creates personalized outreach drafts based on:

- Conversation content
- Identified needs
- Pain points
- Recommended next steps

---

## Example Outputs