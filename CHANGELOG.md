# VALOSTATS — Changelog 🗒️

## 🏷️ v1.0 “FOUNDATION” — 2026-08-09 *(first public release)*

The launch build. Everything below shipped in v1.0:

### 📊 Core
- **10 working tabs** — Overview · Matches · Team · Opponents · Agents · Maps · Weapons · Skins Armory · Assistant · Leaderboard
- **Live sync** via HenrikDev API (account, MMR, matches, RR history, AP leaderboard) — key stored only in-browser
- **Simulated demo mode** with seeded RNG for anyone without a key (SIMULATED badge shown)
- Auto-sync every 5 min + new-match toast + freshness chip

### 🎨 Visual / UX
- Tracker.gg-style dark dashboard: glass rank panel, official Riot rank icons (change with real rank), floating agent hero (desktop), animated trend tiles, radar + donut charts, map-splash match cards
- **Weapons tab**: real kill-feed telemetry — kill bars, HS%, DPR, first bloods, real gun renders
- **Skins Armory**: all 1,387 official skins, official rarity colors, search/filters, ♥ ownership (localStorage), per-rarity completion bars, Current Loadout equipping
- Full 10-player scoreboards per match (ACS, K/D/A, econ, FB, agent icons) + RR change per match

### 📱 Mobile
- Responsive overhaul: compact match cards (stats fold under map name), stacked weapon rows with stat chips, micro-phone skin-grid breakpoint, global `min-width:0` anti-overlap hardening

### 🔐 Privacy / Deploy
- No secrets in code — demo profile generic (`Player #0001`)
- Public release on GitHub + GitHub Pages hosting

---

## 🔮 Roadmap (not in v1.0 — coming later)

| Idea | Target |
|---|---|
| 🥉 Road-to-Bronze tracker (RR graph to next rank) | v1.1 |
| 👯 Duo comparison — side-by-side with a friend | v1.2 |
| 📔 Session diary (today's matches grouped, W/L streak) | v1.2 |
| 🌐 Netlify mirror deploy | ops |
| 🎞️ Kill-feed replay per match | v1.3? |

> v1.0 is the foundation — clean, fast, live. We build UP from here. 🚀
