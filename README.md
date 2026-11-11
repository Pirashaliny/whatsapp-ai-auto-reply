# WhatsApp AI Auto Reply (n8n)

AI-powered WhatsApp auto-reply built with n8n, Meta WhatsApp Cloud API and Google Gemini.

## Flow
WhatsApp Trigger -> Switch -> Edit Fields -> AI Agent (Gemini) -> Send message

## Setup
1. In n8n: Import from File -> select the JSON file
2. Create WhatsApp OAuth and WhatsApp API credentials
3. Add your Google Gemini API key
4. Set your Phone Number ID in the Send message node
5. Publish the workflow
