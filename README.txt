TRADING STRATEGY VAULT — AI BUILD

Admin password: Fx11

This build keeps the Strategy Vault library and adds:
- AI Analysis with OpenAI + Gemini + Groq
- Chart screenshot upload and 3-AI consensus: UP / DOWN / STOP
- Confidence + risk level + short reason
- 10–16 second safety/consensus display delay
- Future Signals: multiple scenarios across the next 30 minutes
- Money Management: balance, risk/trade and daily risk calculator
- Browser notification permission for AI results / new strategy publishing
- Accent color system and PWA install support
- Existing strategy screenshots, videos, notes, admin edit/delete and backup

AI CONFIG
Open `ai-config.js` and replace the placeholder keys:
PASTE_OPENAI_API_KEY_HERE
PASTE_GEMINI_API_KEY_HERE
PASTE_GROQ_API_KEY_HERE

You can use only Groq if you leave the other two placeholders. The AI engine automatically uses every configured provider.

IMPORTANT SECURITY
This is a GitHub-only frontend. API keys placed in `ai-config.js` are visible to website visitors. Do not use an unrestricted secret key on a public GitHub Pages site. For proper secret protection, use a backend/proxy.

GROQ VISION
The build uses `qwen/qwen3.6-27b` for chart vision and JSON output.

LOCAL STORAGE
Strategies and uploaded media are stored in IndexedDB on the current browser/device. Export/Import Backup is included.

For automatic syncing of strategies between different phones/devices, a cloud backend is still required.
