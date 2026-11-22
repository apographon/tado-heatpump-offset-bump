# Changelog

## 2026-11-22 — initial public-ready package

- Documented Offset-Bump pattern (Tado demand → `hc1_offsettemp` via EMS-ESP / Home Assistant)
- Added sanitized daily starts / outdoor-temp CSV and weekly energy comparison
- Added SVG charts (starts vs AT, weekly averages)
- Added example YAML (helpers, demand template, stepped write script, bump automation)

### Field timeline (summary)

| When | Change |
|------|--------|
| ~7–13 Nov 2026 | Fixed weather-curve offset (+2…+4); high start counts |
| 14 Nov evening | Offset-Bump enabled |
| 15–16 Nov | Debounce shortened (5→2 min), Ist+2 / cap basis+3, demand ≥20% |
| 15–21 Nov | Avg ~8.6 starts/day vs ~13.9 the week before |
