# 24 RAPID Inter Unit Football Championship 2026-27

Single-page tournament app: pool draw, fixtures across four grounds,
live match clock and scores, points table, knockout bracket, squads and awards.

## Hosting

`index.html` is the whole application. It needs no build step and no server.
Any static host will serve it as-is.

## Shared database (optional)

Open `index.html`, find `var DB = {` near the top of the script, and paste the
Supabase Project URL and anon public key. Setup instructions and the SQL to run
are in the comment directly above that block.

Left blank, the app runs entirely offline and stores everything in the browser.
