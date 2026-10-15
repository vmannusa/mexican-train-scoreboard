# Mexican Train Scorecard

A one-phone scorecard for Mexican Train dominoes. At the end of each round, pass the phone around: each player snaps a photo of their leftover dominoes and AI counts the dots, or just types an easy number, or taps **I'm out (0)**.

**Live app:** https://vmannusa.github.io/mexican-train-scoreboard/

## How it works
1. Enter players (in turn order) and the set (Double 12 = 13 rounds, Double 9, Double 15).
2. Tap **Score this round** and the app walks through each player:
   - **📷 Scan tiles:** Gemini lists the dots on each half of every tile; the app adds them up and shows the tiles so you can double-check before confirming.
   - **Type it** or **I'm out (0)** for quick ones.
3. The scorecard shows every round, running totals, and the leader (lowest score wins). Tap any score to fix it.
4. Everything is saved on the phone, so refreshing doesn't lose the game.

## Setup
Get a free Gemini API key at https://aistudio.google.com, then paste it into ⚙︎ Settings → **Test key**. The key is stored only in that phone's browser, never in this repo.

## Tech
Single `index.html` (vanilla HTML/CSS/JS) hosted on GitHub Pages; calls the Gemini API directly from the browser.
