# Improved Team Mode

Team mode for **Super Battle Golf** with **up to 4 teams**. The base game only allows 2, so this makes duos, squads or a 2v2v2v2 possible.

> **Everyone in the lobby must install this mod, not only the host.** A player without the mod cannot see the teams, the team colors or the team scores.

## Features
- **A new game mode in the game's own menu: "Improved Teams"** (French: "Équipes Améliorées"), right next to "Free for all" and "Teams". Pick it and you are done, nothing else to switch on
- Up to 4 teams (Red, Blue, Green, Yellow), assigned player by player from the match setup menu
- **Two ways to score a team**
  - **Points**: the team total is the sum of its players' points, added up over the whole game and reset when you are back on the driving range
  - **Rounds**: like the game's own team mode, each hole is a round. The team with the most players finishing the hole wins the round (a tie gives the round to every tied team). Optional **End hole early** setting, for the host
- Team scoreboard: one header per team with its total, players listed under their team with their name in the team color, and the **team rank** on every row (tied teams share the same rank)
- **End-of-course podium**: the top 3 teams with their players' avatars, shown while the game counts down back to the driving range
- **The driving range never counts**: goals scored while you wait for the game to start give no points and no rounds
- A team badge on every player's screen (bottom left), in the game's style
- Skin color and name tag color follow the team
- Friendly fire toggle (off by default: teammates cannot hurt each other)
- Everything is synced from the host: guests see their team, the colors, the scores and the podium
- Works together with **Custom_Scoring** in Points mode. In Rounds mode points no longer decide who wins, so its menu section is hidden and it is switched off until you leave Rounds mode
- French and English

## How to use
1. The host and every guest install the mod.
2. Host (on the driving range): open the match setup menu and set **Mode** to **Improved Teams**.
3. Go to the **Rules** tab and scroll down to the **Team Mode** section. Choose the **Team score** (Points or Rounds), the number of **Teams** (2 to 4), then pick a team for each player.
4. Start the match. When the game ends, it goes back to the driving range and the team scores reset.

The game's own "Teams" mode (2 teams) is still there: choose it in the same menu and Team Mode switches itself off.

## Installation
Install it with your mod manager, or place the package so the DLL ends up at `BepInEx/plugins/Team_Mode.dll` (BepInEx is required). The Nexus package already contains the `BepInEx/plugins` folders: extract it into the game folder and it replaces the old version.

## Version
- `0.3.1`
