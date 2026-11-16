SAGINAW ORTHODONTICS — ORIGINAL SHARED REBUILD

Upload ONLY index.html and config.js to Netlify Drop. Do not upload the backup JSON or SQL file.

Uses your existing Supabase project and project_data table. Your existing admin must sign in with an email magic link. The first successful admin sign-in initializes the shared original project from the uploaded project backup, only if the original_shared_board key does not already exist.

IMPORTANT: This is a first working integration, not a production-audited multiuser application. Original local team labels are preserved, but only Supabase admins can access the complete board. Updates are shared and other users see them on refresh or within about 15 seconds. Simultaneous edits can overwrite one another because the board is saved as one JSON document. Avoid simultaneous edits and keep periodic JSON backups. Do not store patient health information.

Supabase Authentication > URL Configuration: set Site URL and Redirect URLs to your Netlify URL.
