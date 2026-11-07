# Changelog — 2026-11-07
- Berkshire card reads the shared Micron quote for `BRK.B` when `brkb-dashboard.cashcache.workers.dev` is down, and reads build, B-equivalent shares, 10-Q BVPS, next earnings, and `whatsNewThisWeek` from `BRK_DATA`. Removed the hardcoded ~$352.8 / ~1.54x row. Scan schedule is Mon–Sat 9:00 SGT. P/E stays blank because data.js does not publish one.

# Changelog — 2026-11-02
- **What’s new this week** moved to its own **What’s new** tab (all eight company dashboards + AI Datacenter on one feed). Overview tab keeps the card grid, summary, and open issues. Deep-link `#whats-new`.
- Feed still merges `whatsNewThisWeek` from each bot’s data.js; purple ticker·company badges; teal **AI Datacenter** badge for DC rows. Empty state if no items.
- Cards still show a 1–2 line What’s new teaser when that bot has items.
- Alphabet (`GOOG_DATA`) and Berkshire (`BRK_DATA`) marked live and loaded.
- Open issues: removed stale GOOG/BRKB 404 bullet and Investment hub preview note; kept Cloudflare import + Berkshire BVPS notes.
