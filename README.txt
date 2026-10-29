The Nightmare on Plat Street — static website package

This is a PREVIEW build. GAME_LIVE=false in app.js prevents real door openings and submissions.
The artwork, 30 numbered door hotspots, player roster, organizer login, review controls and server integration are included.
Upload the contents of this folder to a GitHub Pages repository (index.html at site root) to view it online.
Before enabling live play: perform end-to-end authentication and door-opening tests in a separate staging project, verify CORS, challenge-specific validation, rate limits and anti-impersonation limitations.
Do NOT switch GAME_LIVE to true merely to test on the live game; doors are permanent.
Organizer login requires the separate Supabase Auth account, never share the password.
The 30 images are transparent PNG assets; all door images are mapped by fixed door number.
