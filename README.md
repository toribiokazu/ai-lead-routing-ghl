# AI Lead Routing & Qualification for GoHighLevel + n8n

An AI-powered lead qualification workflow using GoHighLevel, Groq, Slack, and n8n Cloud.

## What It Does

1. Receives a GoHighLevel lead webhook.
2. Normalizes the lead payload.
3. Validates that the lead has an email address.
4. Uses Groq to score and classify the lead as hot, warm, or cold.
5. Updates GoHighLevel with tags, tasks, opportunities, or nurture enrollment.
6. Posts a rich Slack notification to the sales team.
7. Logs the final routing result.

## Included Files

- `workflow.json` - n8n workflow import file
- `docs/documentation.docx` - detailed workflow process documentation
- `docs/setup-guide.md` - setup checklist
- `docs/workflow-diagram.png` - workflow screenshot

## Required Credentials

- GoHighLevel API key
- Groq API key
- Slack Bot OAuth token

## Setup

Import `workflow.json` into n8n, add the required credentials, replace placeholder GoHighLevel IDs, configure Slack channels, and activate the workflow after testing.
