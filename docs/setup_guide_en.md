# Setup Guide for n8n AI Automation Workflow

## Prerequisites
- n8n installed (local or cloud instance)
- OpenAI or Anthropic API key
- Google Sheets API credentials (if using Google Sheets)
- Telegram bot token and chat ID (if using Telegram)

## Installation
1. Install n8n locally or sign up for n8n cloud.
2. Import the workflow from `workflows/sample_workflow.json`.
3. Configure the nodes with your API keys and credentials.

## Configuration
- **OpenAI/Anthropic Node**: Set your API key in the credentials.
- **Google Sheets Node**: Provide your spreadsheet ID and authenticate.
- **Telegram Node**: Set bot token and chat ID.

## Testing
Use the sample input from `examples/sample_input.json` to test the workflow via the webhook.

## Usage
Send a POST request to the webhook URL with a JSON payload containing the task description.
