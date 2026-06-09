# FC Online VIP Revamp — Wireframe v2.2

Interactive wireframe for the Football Complex VIP page revamp (FC Online Vietnam / Garena).

**Live demo:** deploy via Vercel (see below)

---

## Screens

| Screen | Description |
|---|---|
| ① Main Map | Football Complex isometric map — Pay Zone, Play Zone, SVIP/VVIP towers, daily gift interaction |
| ② Reward Tree | Pay Tree & Play Tree with progressive reveal + Activity Snapshot |
| ③ Hall of Fame | Annual leaderboard — Top 100 Pay & Play |

## Features in this wireframe

- Dual-track tier system (Pay + Play)
- 12-month building schedule per zone
- Progressive reveal reward tree (past → current → +1 → +2 faded → hidden)
- Daily gift on current month's building (click to claim, resets 00:00 VN time)
- Birthday gift overlay (seasonal state)
- Activity Snapshot in Play Tree (tháng này vs tháng trước)
- SVIP/VVIP tower landmark (annual milestone)
- Hall of Fame with monthly titles (MVP, Iron Man, Legend of the Year)
- Badge states: Default / 🔥 Top 50 / ★ Legend

## Deploy to Vercel

```bash
# 1. Push to GitHub
git init
git add .
git commit -m "fc-vip wireframe v2.2"
git remote add origin https://github.com/YOUR_USERNAME/fc-vip-wireframe.git
git push -u origin main

# 2. Import on Vercel
# Go to vercel.com → New Project → Import from GitHub
# Framework: Other (static)
# Root directory: ./
# No build command needed
```

Or use Vercel CLI:
```bash
npm i -g vercel
vercel
```

## Docs

- [`docs/feature-spec.md`](docs/feature-spec.md) — Feature specs & recommendations not in original brief v1.0.1

## Version history

| Version | Changes |
|---|---|
| v2.2 | Daily gift on map buildings, Activity Snapshot, birthday overlay, footer update |
| v2.1 | 8 fix comments applied (SVIP position, tree milestones, badge states, Phase 3 scope) |
| v2.0 | Rebuilt from brief v1.0.1 — removed Central Club House, correct layout spec |
| v1.0 | Initial wireframe |
