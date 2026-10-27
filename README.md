# Shein Order Assistant

A Telegram-based n8n workflow for assisting with SHEIN links and order-related conversations.

## Setup
1. Import `workflow.json` into n8n.
2. Reconnect Telegram and AI credentials in n8n.
3. Replace any placeholder values with your own configuration.
4. Test with a Telegram test bot before production use.

## Security and testing
Do not commit API keys, access tokens, webhook URLs, private customer data, or personal email addresses. This repository needs the sanitized workflow export added as `workflow.json`. End-to-end testing is not yet confirmed.