# aibusiness.press content workflow (manual publish)

This repo is set up for a queue-driven workflow.

## Trigger file
- `posts/queue.md`

## Command phrases (in Telegram chat)
- `add to queue: <topic>` → append under **## Pending**
- `show queue` → list all pending topics
- `publish now` → generate the top pending topic immediately
- `pause` → stop watching queue.md
- `resume` → resume watching queue.md
- `show published` → list everything in Published

## What “publish now” does (manual mode)
For the top item under **## Pending**:
1. Web research (facts, pricing, examples)
2. Write website post → `posts/drafts/<slug>.md`
3. Create paste-ready formats:
   - LinkedIn (<= 1200 chars)
   - X thread (8–10 tweets, numbered)
   - Substack (subject < 50 chars + full body)
4. Move the topic line from Pending → Published in `posts/queue.md` and add:
   - date
   - Website path + Netlify preview URL (if known)
   - Paste blocks for LinkedIn/X/Substack
5. Message owner on Telegram with:
   - ✅ Published: <title>
   - 🌐 Website: <url>
   - 💼 LinkedIn: (paste-ready)
   - 🐦 Twitter: (paste-ready)
   - 📧 Substack: (paste-ready)

## Links
- Domain: https://aibusiness.press
- Netlify: https://aesthetic-sunshine-9d0e30.netlify.app
- Substack: https://substack.com/@aibusiness3
