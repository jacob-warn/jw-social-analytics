# Jacob Warn — Social Analytics Dashboard

Live dashboard at: `https://YOUR_USERNAME.github.io/jw-social-analytics/`

## Files

- `index.html` — the full dashboard (self-contained, no build step)
- `data/analytics.json` — weekly data updated by the analytics script each Monday

## Updating data

The Monday analytics task writes to `data/analytics.json` and runs:

```bash
git add data/analytics.json
git commit -m "Analytics: week ending [date]"
git push
```

GitHub Pages redeploys automatically within ~60 seconds.
