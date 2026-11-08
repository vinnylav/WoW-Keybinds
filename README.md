# Keybind Atlas

A small static page for planning WoW action bar keybinds so every class keeps the same muscle memory.

1. **Bars**: match your real action bars. Import your Edit Mode layout string (or use a preset / shape bars by hand) and import your keybinds from `bindings-cache.wtf`, or click a button and press its key. "Send to WoW" gives you `/run` lines that apply the keybinds in game.
1. **Categories**: paint named groups of buttons (Builders, Interrupt, Defensives…) once.
1. **Classes**: add each class or spec and drop its abilities into those categories. Each ability remembers which category it belongs in and gets flagged if it ends up outside it.
1. **Compare**: see every class on the same map, plus a category-by-category table.

Everything is saved in your own browser (localStorage). Use **Export JSON** to back up or share a layout and **Import** to load one.

Icons: type a Wowhead icon name (for example `spell_holy_avenginewrath`), paste an image URL, or drop/paste a screenshot crop.

## Hosting

It is a single `index.html` with no build step. GitHub Pages serves it from the `main` branch root.

## Credits

WoW Forever class spellbooks (`data/forever-spells.js`) were compiled from [wclbox's WoW Forever database](https://wowforever.wclbox.com/en) on 2026-11-08 (client build 1.60.1.x). Spell names were tidied where the site's translation differed from the in-game name.

Frame and button art comes from [warcraftcn/ui](https://github.com/TheOrcDev/warcraftcn-ui) (MIT, see `assets/wc/LICENSE-warcraftcn.md`). World of Warcraft is a trademark of Blizzard Entertainment; this project is not affiliated with Blizzard.
