# Ultimate Ludo Game: Design Document

Moved from the misnamed root file `ludo-ultimate-desihn-146.html` (text design notes, not HTML).

## Overview

Single-file HTML5/CSS3/JavaScript Ultimate Ludo supporting 2–6 players (Red, Blue, Green, Yellow, Pink, Black), with profiles, coins/diamonds, settings, support UI, notifications, and optional AI.

## Core rules (summary)

- 4 tokens per player; start at home (`-1`); roll 6 to enter the board.
- Clockwise shared path; color home columns; exact roll to finish.
- Capture on non-safe tiles; safe zones include start tiles and star tiles.
- First player to seat all four tokens home wins.

## Product surface (summary)

Home screen with profile/level/currency, table selection (2/3/4/5/6, team, private, jungle), bottom nav (events/battle/chat/social), settings (sound/music/language/privacy), support/FAQ, welcome-back and inactivity popups, level progression economy.

## Technical constraints

Vanilla single HTML file preferred for prototypes in this repo; client-side only; responsive UI.

See also the HTML prototypes listed in `README.md` / `demos.html`.
