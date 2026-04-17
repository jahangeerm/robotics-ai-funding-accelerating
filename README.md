# Robotics & embodied AI funding is accelerating

A single-page Q1 2026 funding snapshot prepared as **fundraise context for Auki** —
spatial infrastructure for robotics & AR fleets.

**Live page:** https://jahangeerm.github.io/robotics-ai-funding-accelerating/

## What this is

- One self-contained `index.html` (no build step, inline SVG charts, no JS deps).
- Pulls Q1 2026 robotics venture funding figures from a public source
  ([Robotomated, Mar 27 2026](https://robotomated.com/learn/market/robotics-funding-q1-2026)).
- Frames the market context against Auki's positioning as the shared spatial
  coordination layer for multi-vendor robotics & AR deployments.

## Caveats

- Robotics funding totals vary significantly between trackers (CB Insights,
  PitchBook, Crunchbase, sector-specific aggregators). This page uses one
  source for narrative consistency. **Reconcile against your preferred analyst
  before using these figures in legal documents or data rooms.**
- Figures are public; framing is intentionally Auki-aligned.

## Edit & redeploy

```bash
# edit index.html
git add index.html
git commit -m "update funding figures"
git push
# GitHub Pages rebuilds automatically (~30–60s)
```
