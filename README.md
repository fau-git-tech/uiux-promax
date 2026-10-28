# uiux-promax

Slide decks built with the `slides` skill from [nextlevelbuilder/ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill).

## Decks

- [`decks/rivibi/`](decks/rivibi/index.html): 5-slide seed pitch for RIVIBI, a concept for vibration-based predictive maintenance in Southeast Asian factories. It has charts for market growth and competitive positioning. **All figures are illustrative.** Open `index.html` in a browser and use the arrow keys to move between slides.

## Skill

The `slides` skill lives in `.agents/skills/slides`, and Claude Code finds it through the link at `.claude/skills/slides`. Reinstall or update it with:

```bash
npx skills add https://github.com/nextlevelbuilder/ui-ux-pro-max-skill --skill slides
```

Note: `references/html-template.md` loads Chart.js from `chart.umd.min.js`, which doesn't exist in Chart.js 4.4.1. Use `https://cdn.jsdelivr.net/npm/chart.js@4.4.1/dist/chart.umd.js` instead.
