# Keybind Atlas

A small static page for planning WoW action bar keybinds so every class keeps the same muscle memory.

1. **Zones**: paint named areas (Builders, Interrupt, Defensives…) onto the key grid once.
2. **Classes**: add each class or spec and drop its abilities into those zones. Each ability remembers which zone it belongs in and gets flagged if it ends up outside it.
3. **Compare**: see every class on the same map, plus a zone-by-zone table.

Everything is saved in your own browser (localStorage). Use **Export JSON** to back up or share a layout and **Import** to load one.

Icons: type a Wowhead icon name (for example `spell_holy_avenginewrath`), paste an image URL, or drop/paste a screenshot crop.

## Hosting

It is a single `index.html` with no build step. GitHub Pages serves it from the `main` branch root.

## Credits

Frame and button art comes from [warcraftcn/ui](https://github.com/TheOrcDev/warcraftcn-ui) (MIT, see `assets/wc/LICENSE-warcraftcn.md`). World of Warcraft is a trademark of Blizzard Entertainment; this project is not affiliated with Blizzard.
