OCCL COMPLETE WEBSITE BUNDLE

1. Upload all files to the root of your GitHub occl repository, replacing old pages.
2. Use these hyphenated filenames: submit-record.html and submit-level.html (the links in the pages use these names).
3. In supabase-config.js replace PASTE_PROJECT_URL_HERE and PASTE_PUBLISHABLE_KEY_HERE with your project's URL and publishable key. Never put a secret/service-role key in browser code.
4. The site expects the table columns shown in supabase-schema.sql. Because you already ran earlier SQL, inspect Table Editor first; existing tables may have different columns. Do not blindly rerun if columns differ.
5. Replace CREATOR_EMAIL_HERE in supabase-schema.sql with your exact creator email, then run/reconcile the policies in SQL Editor.
6. Create the creator user under Supabase Authentication > Users, then sign in at editors.html.
7. Commit all files to GitHub main; Pages should redeploy automatically.

This is an implementation bundle, not verified against your particular Supabase project. Test submissions and creator-only approval before relying on it. Never put a secret/service-role key in public code.
