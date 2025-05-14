# Bluish

Dark themes with blue accents for Plasma 5. This repo contains Plasma style and color scheme to theme the GUI. For a complementary color scheme to theme the CLI, check out the [Pinkish](https://github.com/svhl/pinkish) repo.

## How to use

```bash
git clone https://github.com/svhl/bluish
cd bluish
mv ./desktoptheme/* ~/.local/share/plasma/desktoptheme
mv ./color-schemes/* ~/.local/share/color-schemes
```

Then, change the Plasma Style and Colors to Bluish in settings.

## Themes

### Bluish Plasma Style

Based on **K10neBlack** by **phob1an** and **Materia Manjaro Dark** by **freefreeno**. Goes well with Papirus Dark icons.

Fixes:

- Removed the busy widget SVG since it's janky.
- Added microphone icon.
- Removed tranlucency on a few plasmoid icons like volume and clipboard. This is because the translucent regions shimmer when the cursor is hovering over the icon.

Wontfix:

- A few plasmoid icons like volume and clipboard brighten up on hover, even if they have solid fill with full opacity. More like a cantfix than a wontfix.

### Bluish Colors

Based on **Sweet** by **EliverLara** and **Rosé Pine**. Goes well with Papirus Dark icons.

## License

The GNU General Public License v3.0
