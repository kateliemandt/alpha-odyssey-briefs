# Alpha Odyssey — Briefs

The long-form companion to [alpha-odyssey-overview](https://github.com/kateliemandt/alpha-odyssey-overview). Same content, but each brief gets its own screen, with a sticky sidebar index and a magazine-style layout so a single workshop has room to breathe.

## Structure

```
index.html     — shell, CSS, renderer with hash routing
data/          — identical data files to the overview site
```

Routes:

- `#/` → landing (all briefs as cards, grouped by week + side quests)
- `#/b/<entry-id>` → a single workshop/challenge brief
- `#/q/<quest-id>` → a single mastery side quest

## Running locally

Open `index.html` directly, or serve:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## When to use which site

- **Overview** → at-a-glance review, comparing levels side by side, scanning a whole week.
- **Briefs** → focused reading, printing a single brief, sharing a specific workshop with a parent or specialist.
