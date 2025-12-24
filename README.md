# Bluish

Dark themes with blue accents for KDE Plasma 6. This repo contains Plasma style and color scheme to theme the GUI. Goes well with **Papirus Dark** icons.

For a complementary color scheme to theme the CLI, check out the [Pinkish](https://github.com/svhl/pinkish) repo.

## How to use

```bash
git clone https://github.com/svhl/bluish
cd bluish
mv ./desktoptheme/* ~/.local/share/plasma/desktoptheme
mv ./color-schemes/* ~/.local/share/color-schemes
mv ./gtk-4.0/* ~/.config/gtk-4.0
```

Then, change the Plasma Style and Colors to Bluish in settings.

## Themes

### Plasma Style

![Plasma Style](https://github.com/user-attachments/assets/aa9e2ef2-83ed-4d13-ab31-2fdacf7ff2b2)

Based on **K10neBlack** by **phob1an** and **Breeze** by **KDE**.

### Colors

![Colors](https://github.com/user-attachments/assets/83fefa0e-408e-4923-9860-7d09efb12ce9)

Based on **Rosé Pine** and **Breeze Dark** by **KDE**.

### GTK4/Libadwaita

![Libadwaita](https://github.com/user-attachments/assets/75f7a56f-e51d-4b7f-8a6d-9c379b0d9e46)

Force applications that use this framework to follow the Plasma color scheme instead of the default Adwaita colors.

For Flatpak apps, install Flatseal to make this process easier. Then, go to All Applications > Filesystem, and add `xdg-config/gtk-4.0:ro` under Other files.

Source: [Simple hack to tinting/theming Libadwaita GTK4 apps in KDE Plasma — KDE Discuss](https://discuss.kde.org/t/simple-hack-to-tinting-theming-libadwaita-gtk4-apps-in-kde-plasma/29444)

## License

The GNU General Public License v3.0
