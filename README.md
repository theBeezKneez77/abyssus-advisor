# ⚓ Abyssus Build Advisor

A quick, phone-friendly planner for [**Abyssus**](https://store.steampowered.com/app/1721110/) (v1.3) builds. Pick your weapon, mods, and ability, then get blessing and upgrade recommendations that blend online community consensus with **our own group's run data**.

### ▶ Live: https://thebeezkneez77.github.io/abyssus-advisor/

No install, no login — it runs entirely in your browser.

---

## What it does

It mirrors the in-game decision order in three steps:

1. **Weapon setup** — choose weapon, primary/secondary mod, and ability. Tap a **starter combo** to auto-fill a loadout with the best track record.
2. **Blessing slots** — recommended aspects for each of your three slots, with **✓ Proven** pairings called out (e.g. Blood + Anchor, Lightning on the bow, Ocean on the Cube). It stops you doubling up a blessing and warns you if nothing can damage Un'glu crystals.
3. **Blessing upgrades** — the priority order to take for each blessing (Take first / if available / skip), plus charm pairings and milestone notes.

Finish and you get a one-glance **"Start your run"** loadout summary.

## Run Log — this is the good part

Log your end-of-run screen and the tool accumulates what actually works for us:
- Win rate, average damage, and best runs.
- A blessing **tier board** where each rating = **community consensus ⊕ our logged runs (50/50)**. Hover any tier badge for the breakdown. The more we log, the smarter it gets.

## On your phone

- Open the link → **Share → Add to Home Screen** for an app-style icon.
- Mobile-first layout; works offline after the first load.

## Sharing run data with the group

Each phone keeps its **own** Run Log (stored in that browser). To pool everyone's runs:
1. One person opens the **Run Log** tab → **Export** → sends the `abyssus-runs.json`.
2. Everyone else hits **Import** and picks that file. Runs merge (no duplicates).

That shared data is what powers the blended tier ratings.

## Notes

- Phase 1: fully client-side. No accounts, no analytics — your data never leaves your browser except when you Export.
- Build data from [abyssus.wiki.gg](https://abyssus.wiki.gg) + community sources (Steam, Game Rant) + our own runs.
- Found a wrong mod name or tier? Tell me and it's a quick fix.
