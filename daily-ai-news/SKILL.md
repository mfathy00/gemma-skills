---
name: daily-ai-news
description: Get the latest AI news. Use this when the user asks about AI news, latest AI updates, new AI models, or AI announcements.
---

# Daily AI News

## Instructions

When the user asks for AI news, you MUST call the `run_js` tool with these exact parameters:
- **filename**: `index.html`
- **data**: `{}`

The tool will return a JSON object containing a `result` field with the latest AI news stories.

After receiving the result, present the news stories to the user clearly, keeping the titles and URLs from the response.
