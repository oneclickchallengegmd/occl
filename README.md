# OCCL — One Click Challenge List

## Files
- `index.html` — main list page. Framy and Huh have their level IDs, SpikeGmd as publisher, and the supplied YouTube links.
- `records.html` — public approved-records page.
- `submit-record.html` — record submission form preview.
- `submit-level.html` — suggest-a-level form preview.
- `editors.html` — creator panel layout preview.

## Important functionality note
This is a static GitHub Pages website. The record and level forms currently only show a preview message; they do not send or save submissions. The creator panel is not a secure login and approval buttons are intentionally disabled. To make submissions persistent and ensure only the creator can approve/reject them, connect a backend/database and real authentication with server-side access rules. Do not rely on hiding a page or secret URL for security.

## Publish updates
Upload/replace these files in the root of your existing `occl` GitHub repository. GitHub Pages will redeploy automatically after the commit.
