# PostPilot Starter

A browser-based starter for PostPilot — Create Once. Publish Everywhere.

## Run it
1. Extract the ZIP.
2. Open `index.html` in a modern browser (Firefox or Chrome).
3. Create a draft and save it. Drafts are stored in this browser's local storage.

## What works
- Responsive dashboard
- Draft creation, editing, deletion
- Platform selection for Facebook, Instagram, TikTok, YouTube, WhatsApp Business, LinkedIn, Threads, and X
- Image/video preview (starter limit: 5 MB)
- Content library and publishing history shell
- Explicit notice that social publishing is not connected

## What does not work yet
- Real OAuth account connections
- Actual social publishing
- Cloud database or multi-user accounts
- Scheduling workers, analytics, or billing
- Secure cloud media storage

The "Publish Everywhere" button deliberately does not publish anything; it explains that official integrations must be configured first. This prevents false success claims.

## Recommended next implementation stages
1. Move from local storage to a hosted database and authentication.
2. Implement secure server-side OAuth/token storage.
3. Integrate Meta Facebook Pages/Instagram after confirming eligibility and permissions.
4. Add Threads, LinkedIn, YouTube, TikTok, X and a separate WhatsApp Business messaging workflow.
5. Add per-account publishing jobs, verified status, retry safety and duplicate prevention.
