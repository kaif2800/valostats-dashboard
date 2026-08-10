# VALOSTATS — Valorant Stats Dashboard 🔫📊

A full **Tracker.gg-style Valorant stats dashboard** in a single HTML file — no build step, no backend. Open it in any browser and it just works.

> ⚠️ **Private project.** Not affiliated with Riot Games. Personal stats tool.

![Version](https://img.shields.io/badge/version-1.2-f2b363) ![Status](https://img.shields.io/badge/status-live-ff4655) ![Type](https://img.shields.io/badge/app-single--file-00c3ff)

> 🏷️ **v1.2 “MOMENTUM”** — Road-To tracker, Session Diary, match grades, tilt detector, Enemy Dossiers, bottom thumb-nav, More sheet, pro SVG icons, back-to-top, quick-jump links. See [CHANGELOG.md](CHANGELOG.md).

---

## ✨ Features

| Tab | What it shows |
|---|---|
| 🏠 **Overview** | Live rank card (official Riot rank icons that change with your rank), RR progress bar, peak rank, K/D / ADR / HS% tiles with trend arrows, season totals, accuracy body-zone chart, act-by-act history, performance radar, win donut |
| 🎮 **Matches** | Match cards with map splashes, MVP badges, full 10-player scoreboards (agent icons, ACS, K/D/A, econ), RR change per match, half-by-half scores |
| 👥 **My Team** | Detects your real party-mates from synced matches |
| ⚔️ **Opponents** | Threat tracking on players you keep facing |
| 🦸 **Agents** | Per-agent performance with official portraits |
| 🗺️ **Maps** | Per-map records with official splash art |
| 🔫 **Weapons** | Real kill telemetry — kill bars, HS%, DPR, first bloods, arsenal insights |
| 🗄️ **Skins Armory** | All **1,387 official skins** with real renders & rarity colors — ♥ mark what you own, completion bars per rarity, current-loadout equipping |
| 🧠 **Assistant** | Per-map agent fit scores for your playstyle |
| 🏆 **Leaderboard** | Real top-25 leaderboard for your region |

Extras: auto-sync every 5 min with new-match toast, freshness indicator, fully responsive mobile layout, simulated-data fallback mode.

---

## 🚀 How To Use

1. Download **`index.html`**
2. Open it in any browser (works on phone too 📱)
3. Tap **CONNECT LIVE DATA** and enter:
   - Your **Riot ID** (`Name#Tag`)
   - Your **region** (e.g. `ap`)
   - A free **[HenrikDev Valorant API](https://docs.henrikdev.xyz/) key** (`HDEV-…`)

Your key is stored **only in your own browser's localStorage** — never in this file, never sent anywhere except the HenrikDev API.

---

## 🔌 Data Sources

- **Live stats:** [HenrikDev Unofficial Valorant API](https://docs.henrikdev.xyz/) (account, MMR, matches, RR history, leaderboard)
- **Official art assets:** [valorant-api.com](https://valorant-api.com) (rank icons, agents, weapons, maps, skins, content tiers)

---

## 📂 Files

```
index.html   ← the entire app (open this)
README.md    ← this file
```

## 🛡️ Privacy Notes

- **No secrets committed** — API keys live only in browser localStorage.
- Honest limits: no third-party API can see *in-progress* matches (Riot restriction) — new matches appear ~1–3 min after they end. Riot also keeps skin inventories private, so armory ownership is marked manually with ♥.
