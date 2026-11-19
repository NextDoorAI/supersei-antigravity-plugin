# Supersei CRM for Google Antigravity

Run your [Supersei](https://supersei.ai) CRM by just asking. This plugin connects Antigravity to your Supersei workspace so you can find and update leads, read full WhatsApp, WhatsApp Web, email, Instagram and Messenger history, manage tasks and meetings, create payment links and see your pipeline, all from a conversation.

## Setup

1. Install the plugin from the Antigravity Marketplace (or `agy plugin install https://github.com/NextDoorAI/supersei-antigravity-plugin`).
2. On first use, Antigravity opens the Supersei sign-in page. Sign in with your Supersei work email (one-time code or password) and pick your workspace.
3. Ask away. Tokens refresh automatically; disconnect any time from **Settings → API keys** in Supersei.

You need a Supersei account. New here? The sign-in page has a **Start a free 30-day trial** link.

## What you can do

- "What follow-ups am I late on today?"
- "Show my newest leads and their pipeline stage."
- "Move this lead to Quotation sent and remind me to call tomorrow at 11."
- "Summarise the WhatsApp and email history with this lead."
- "How does our pipeline look this month?"

The plugin lists everyday CRM tools by default and reaches 500+ more (HR, payroll, service desk, campaigns, admin) on demand through `find_tools`, so your context stays small.

## Safety

- The AI can only do what your Supersei role allows.
- It asks before sending a message, deleting anything or making bulk changes; deletes are soft and can be restored.
- Text inside CRM records is treated as data, never as instructions.

## Contents

| File | Purpose |
| --- | --- |
| `plugin.json` | Plugin manifest |
| `mcp_config.json` | Supersei MCP server (`https://api.supersei.com/mcp`, OAuth sign-in) |
| `skills/supersei-crm/SKILL.md` | How to read complete multi-channel histories and act safely |
| `rules/AGENTS.md` | Always-on safety rules |
| `assets/logo.png` | Supersei logo |

## Support

[supersei.ai/contact](https://supersei.ai/contact) · hello@supersei.ai · [Privacy](https://supersei.ai/privacy) · [Terms](https://supersei.ai/terms)
