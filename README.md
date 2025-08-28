# Inbox App

Lovable (Next.js) approvals UI + serverless API routes for Logistics AI Inbox:
- /api/ingest/email
- /api/drafts
- /api/send
- /api/signed-link

## Step 0 — Bootstrapping (this repo)
1. Install Node 20 + pnpm:
   ```bash
   nvm install 20 && nvm use 20 && corepack enable
   ```
2. Initialize Git and push:
   ```bash
   git init -b main && git add . && git commit -m "chore: step 0 scaffolding"
   git push -u origin main
   ```

## Next
- Add env in Lovable: SUPABASE_URL, SUPABASE_SERVICE_ROLE, SUPABASE_ANON_KEY, STORAGE_BUCKET=docs
- Build Threads/Drafts/Settings/Metrics pages
_Last updated 2025-08-25 23:58_
