# Setup Guide

## 1. Import the Workflow

Import `workflow.json` into n8n Cloud.

## 2. Add Credentials

Create credentials for:

- GoHighLevel API key
- Groq API key
- Slack Bot Token

## 3. Replace Placeholders

Update all placeholders in the workflow:

- `YOUR_PIPELINE_ID`
- `YOUR_HOT_STAGE_ID`
- `YOUR_ENTERPRISE_USER_ID`
- `YOUR_SMB_USER_ID`
- `YOUR_NURTURE_WORKFLOW_ID`

## 4. Configure Slack

Use `chat.postMessage` with the bot token. Invite the bot into every destination channel.

## 5. Configure Groq

Use the endpoint:

`https://api.groq.com/openai/v1/chat/completions`

Recommended model:

`llama-3.1-8b-instant`

## 6. Test

Run test leads for hot, warm, cold, and invalid email cases before activating the workflow.
