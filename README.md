# SiteForge World Clock

Internal caller dashboard. Shows live time for Ljubljana, Manila, and all US time zones with calling-hours status.

## Setup

```bash
npm install
npm run dev        # local dev at localhost:4321
npm run build      # build to dist/
```

## Deploy to Vercel

1. Push this repo to GitHub
2. Go to vercel.com → New Project → Import from GitHub
3. Framework preset: **Astro** (auto-detected)
4. No environment variables needed
5. Click Deploy

Vercel auto-detects `vercel.json` and builds with `npm run build`.

## Features

- Live clock — updates every second
- Ljubljana + Manila in header
- 7 US time zones: Eastern, Central, Mountain, Arizona, Pacific, Alaska, Hawaii
- Color-coded call status: 🟢 CALL NOW / 🟡 CLOSING / 🔴 DO NOT CALL
- Calling hours: 8:00 AM – 9:00 PM local time (per FCC rules)
