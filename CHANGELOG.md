# VALOSTATS — Changelog 🗒️

## 🏷️ v1.2 “MOMENTUM” — 2026-08-09 · 🚧 *still cooking*

The climb + glide update. Your dashboard now *coaches* your grind — and gets you anywhere in one tap.

### ✨ New — Coaching
- 🥉 **Road-To Tracker** (Overview) — current rank icon ⟶ next rank icon, animated shimmer RR bar, "X RR to go", pace estimate from real RR deltas, **PROMOTION IMMINENT** (≥80 RR) and **DEMOTION SHIELD** (≤3 RR) states
- 📔 **Session Diary** (new tab 11) — matches grouped by day; per-session W–L, K/D, avg ACS, best map, **session grade**, net RR; **Week In Review** header card
- 🎓 **Match Grades** — every match graded S/A/B/C/D vs your own pool (percentile composite of K/D, ACS, HS%, win); chips on every match card + diary rows
- 🌡️ **Tilt Detector / Form Rings** (Matches tab) — last-5 form dots, streak chips, 🔥 win-streak and 🛑 tilt-alert banners with coach advice

### ✨ New — Navigation & Icons
- 📱 **Bottom thumb-nav (mobile)** — Home · Matches · Diary · Skins · More; the scrolling tab strip is gone on phones; bars stay synced with active section
- ➕ **More sheet** — slide-up panel with all 11 sections as big tappable tiles; current section outlined
- 🎨 **Pro SVG icon set** — custom angular line icons (dashboard, crosshair, duo, radar, operative, map, cartridge, gem, chat, trophy, calendar) replace emoji icons across nav, bottom bar, tiles
- ⬆️ **Back-to-top** floating button on long scrolls
- 🔗 **Quick Jump** card on Overview — one-tap teleports to Matches / Diary / Weapons / Armory / Assistant
- 🪄 Switching tabs gently resets scroll position

### 📝 Notes
- v1.1 folded into this release (its headliner, the Road-to-Bronze tracker, shipped here as Road-To)
- Desktop sidebar unchanged in behavior (now with SVG icons)
- Works in simulated + live modes; mobile-responsive; zero new external deps
- 🚧 **v1.2 is a work in progress** — more features land under this label before it's tagged final

---

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
| 🥉 Road-to-Bronze tracker (RR graph to next rank) | ✅ shipped in v1.2 as Road-To |
| 📔 Session diary (today's matches grouped, W/L streak) | ✅ shipped in v1.2 |
| 👯 Duo comparison — side-by-side with a friend | v1.3? |
| 🌐 Netlify mirror deploy | ops |
| 🎞️ Kill-feed replay per match | future |

> v1.0 is the foundation, v1.2 is the grind — clean, fast, live. We build UP from here. 🚀
