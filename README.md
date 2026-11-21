# OsmO AI Receptionist

An AI phone receptionist and answering service for your own number, run from your AI app
(Claude, ChatGPT, Cursor, Grok, Codex, OpenClaw, Hermes and any MCP client).

OsmO's AI answers your calls, screens spam, takes each caller's name and what they need, answers
from your Facts and can book them in. From your AI app you can:

- see missed calls and who called and why;
- open any call with its summary, transcript and recording link;
- screen a caller (block, or always put through) straight from one of their calls;
- call back someone who called you in the last 30 days;
- change who is put through, VIP and block lists, caller rules, the assistant and its language.

Every call back and every change is shown to you first and happens only after you say yes.

## Connect

MCP server: `https://api.getosmo.app/mcp/receptionist` (Streamable HTTP, OAuth 2.1 with PKCE and
dynamic client registration; no API key). Sign in once with your phone number.

```sh
claude mcp add --transport http osmo-receptionist https://api.getosmo.app/mcp/receptionist
```

More clients: [`skills/osmo-ai-receptionist/SKILL.md`](skills/osmo-ai-receptionist/SKILL.md).

Needs the OsmO app (https://getosmo.app/app) with a plan and call forwarding on. To have your AI
place calls to businesses and other numbers, see
[OsmO Phone Calls](https://github.com/Mountainheads-Private-limited/osmo-ai-plugins).

Terms: https://getosmo.app/terms · Privacy: https://getosmo.app/privacy · License: MIT
