# Discord + Obsidian AI Agent (n8n)

Gemini-powered Discord bot that reads and writes your Obsidian vault.

## Setup
1. Import `workflow-template.json` into n8n (Workflows → Import from file)
2. Add your own credentials: Discord bot token, Google Gemini API key
3. In Obsidian, install Local REST API plugin, enable HTTP server on port 27123, bind address 0.0.0.0
4. Set your Obsidian API key inside the obsidian node's Authorization header
