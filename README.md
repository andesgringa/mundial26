# Mundial 2026

A self-contained World Cup 2026 results tracker. One HTML file, no
server, no accounts, works fully offline. Spanish-first with an EN/ES
toggle.

## What it does

- 12 group cards with standings that calculate themselves as you enter scores
- A knockout bracket that builds automatically from group results, in
  list or board view
- Stats leaderboards and a sortable team table
- An Argentina tab: squad, top scorers, campaign, and injury log
- A "playing today" strip, with kickoff times shown in your device's timezone
- A dark and a light theme

## How to use it

Just type the goals for each match. Standings, qualifiers, and the
bracket fill in on their own. Tap the clipboard icon on any match to
record scorers and cards.

Your results are saved in your browser on your own device — nothing is
uploaded anywhere. Every visitor starts with a blank tournament and
fills in their own.

## Install on your phone

Open the site in your browser, then use **Add to Home Screen**. It
opens full-screen like an app and keeps working offline.

## Tech

Vanilla JavaScript, no frameworks and no build step. The fixture (teams,
dates, venues) is baked in; results live in `localStorage`.

## Credits

Built by [andesgringa](https://github.com/andesgringa), with development
help from Claude (Anthropic).
