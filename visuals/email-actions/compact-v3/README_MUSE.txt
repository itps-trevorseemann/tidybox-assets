TIDYBOX — FINAL COMPACT EMAIL ACTIONS — MUSE HANDOFF

Approved appearance: pastel rectangular pills with icon on left and label on right. Use ONE default visual state only. NO separate circular icons, hover, or pressed states in the email digest.

Order: Reply; Flag for Sweep; View; Keep; Unsubscribe; Block Email; Block Domain; Clear These. Block Sender is removed.

Contents: 8 transparent icon-only PNGs (128x128), 8 complete compact button PNGs (480x104, render at about 240x52 CSS px if used as images), and approved two-column mobile preview. All button labels are also available as live HTML text; prefer icon-only PNG plus live text for accessibility and email-image blocking.

Desktop: compact buttons in digest rows; wrapping is allowed. Mobile: two columns x four rows as approved. Use email-safe tables and inline CSS, explicit image dimensions, stable public HTTPS asset URLs, descriptive alt text and clickable links wrapping the complete button. No CSS grid/flexbox dependencies. Keep text readable if images are blocked.

Clear These: one action per grouped digest line item, affecting ONLY underlying messages in that specific group; Outlook => Deleted Items, Gmail => Archive. Do not create a persistent rule. Require a secure confirmation page (link scanning in mail clients can prefetch URLs), display group count, then execute only on explicit user confirmation; report partial failures and allow recovery when possible.

All other actions: preserve existing backend logic; do not infer or change meanings.

Upload individual PNGs to the existing tidybox-assets GitHub repository under visuals/email-actions/compact-v3/. Report commit SHA and publicly accessible raw/CDN HTTPS URLs. DO NOT link to github.com HTML blob pages for email image src. Test classic Outlook, Outlook web/new, Gmail web, iOS and Android. Provide actual sent-email screenshots for review.
