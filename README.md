# AUTONEX AI — Business Autopilot

A mobile-first business command center for small businesses and independent service providers.

## V1 modules
- Overview dashboard with live local metrics
- Lead Manager: add, search, filter, update status, delete and export leads as CSV
- AI Support Desk: create customer-reply drafts for human review
- Marketing Studio: create editable social-content drafts
- Automation Hub: save workflow preferences for future integrations
- Analytics: pipeline value, won value, conversion rate and follow-up counts
- Workspace settings

## Run locally
Open `index.html` in a modern browser. No build step or package installation is required.

## Important V1 limitations
- Lead records and settings are stored in browser localStorage on this device only.
- Support and marketing drafts use local templates; no live AI model/API is connected yet.
- Automation preferences are saved locally; no background jobs, WhatsApp, email or social publishing run.
- No multi-user authentication or cloud database is configured.
- Review all generated drafts before sending or publishing.

## Next engineering milestones
1. Add secure authentication and a cloud database with per-workspace access controls.
2. Connect a server-side AI provider for support and marketing drafts.
3. Add verified WhatsApp/email integrations with explicit human approval.
4. Add scheduled background jobs and audit logs.
5. Add billing, usage limits and subscription management.

## Brand
**AUTONEX AI** — Your Business. Your AI. Your Autopilot.
