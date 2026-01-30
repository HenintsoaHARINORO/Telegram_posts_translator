# Telegram Posts Translator

An automated n8n workflow that translates Telegram channel posts into multiple languages and republishes them to target channels.

## Workflow Overview

<img width="1389" height="312" alt="Screenshot 2026-01-30 at 10 22 06" src="https://github.com/user-attachments/assets/f8e80344-b7da-4421-945c-a6a6fb22bf2a" />

## Configure Channel Mappings

Edit the **Create Channel List** node to define your channel mappings:

```json
{
  "sourceChannel": "@your_source_channel",
  "targetChannel": "@your_target_channel",
  "targetLanguage": "Spanish"
}
```

<img width="551" height="793" alt="Screenshot 2026-01-30 at 10 27 02" src="https://github.com/user-attachments/assets/fb08fc88-1e7a-44b0-911c-059b222d0519" />
