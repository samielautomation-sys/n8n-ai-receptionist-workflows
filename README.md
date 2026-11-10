# n8n AI Receptionist Workflows

This repository contains sample n8n workflows for AI-powered WhatsApp reception and customer support flows.

## Included workflows

- `workflows/AI_Receptionist_Refined_v2.json` — WhatsApp AI receptionist with voice, booking, and handover logging
- `workflows/upgraded_ai_receptionist_n8n.json` — upgraded multimodal receptionist with escalation tooling
- `workflows/ai-receptionist-workflow.json` — complete restaurant/guest support workflow example with sheet-based knowledge base

## Important notes

These are example workflow exports and may include credential placeholders. Before importing into n8n, update:

- WhatsApp webhook and credential IDs
- WhatsApp phone number IDs
- OpenAI API credentials
- Google Sheets document IDs and sheet references
- Any secret values or personal URLs

## Recommended import flow

1. Open n8n.
2. Click the menu and choose Import from File.
3. Select one of the `.json` workflow files in `workflows/`.
4. Reconnect credentials for WhatsApp, OpenAI, and Google Sheets.
5. Test with a sample message before production use.

## Security reminder

Do not publish API keys, authentication tokens, OAuth IDs, or live phone numbers in a public repository.

## License

This repository is provided for demonstration and prototyping purposes.
