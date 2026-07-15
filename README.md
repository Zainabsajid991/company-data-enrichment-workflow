# Company Data Enrichment Workflow

## Overview
This project implements a Data Enrichment Workflow using n8n.

## Workflow

1. Receives company data through a Webhook.
2. Calls a mock Company API using the HTTP Request node.
3. Enriches the incoming data using the Set node.
4. Logs the API response time and status.
5. Handles errors using an Error Trigger workflow.
6. Sends an email notification whenever an error occurs.

## Technologies

- n8n
- Beeceptor
- HTTP Request
- Webhook
- Set Node
- Code Node
- Error Trigger
- SMTP Email

## Files

- company-workflow.json
- company-error-workflow.json
