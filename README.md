# ویستان | Vistaan

A Persian RTL toolkit website for small businesses.

## Current starter
- Responsive black-and-white interface
- Public tools without user registration
- Search and category filters
- Editable template-based drafts: captions, content ideas, product descriptions, promotions, weekly calendars, and checklists
- Installable web-app manifest

## Important limitations
The current tools are template-based and run in the browser. They are not AI-powered yet. This starter does not include secure admin authentication, a database, analytics backend, or deployment configuration.

## Planned architecture
- Static frontend, deployable on a static host
- Server-side API routes for AI requests; provider keys stored only as server environment variables
- Google sign-in restricted to the owner, with server-side authorization on every admin endpoint
- Database for admin settings and aggregate usage metrics; avoid unnecessary personal data collection
- Responsive installable web-app experience

## Local preview
Open index.html in a browser or serve this directory with a static HTTP server.

## Next steps
1. Configure hosting.
2. Add secure backend and database.
3. Add owner-only Google authentication and admin reports.
4. Connect an AI provider using a server-side secret.
5. Test mobile and desktop before public launch.

Never commit API keys, OAuth secrets, or admin passwords to this repository.
