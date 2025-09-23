# KDE-EndeavourOS-dotfiles
This repo contains the dotfiles for my KDE Plasma configuration on EOS


1. Clone the repo (choose SSH or HTTPS):
```bash
git clone https://github.com/adrsh1803/KDE-EndeavourOS-dotfiles.git ~/kde-config
```

2. Copy the repo files into place:
```
cp -r ~/kde-config/.config/* ~/.config/
cp -r ~/kde-config/.local/share/* ~/.local/share/
```

3. Log out and log back in to apply changes.

4. Many widgets/themes come from two places:

- User-installed (KDE Store → ~/.local/share/plasma/) — already included in this repo when present.
- OS-installed (pacman / AUR) — live under /usr/share/... and must be installed on the target system.

If a widget or theme is missing after restore, install it via System Settings → Get New [Widgets / Themes / Icons],


### Themes

-SDDM- CBMAnimePetGlobe(1.0) by Pentad
-Global Theme- Breeze
-Application Style- Breeze
-Colours- Sweet-Ambar-Blue
-Plasma Style- Sweet
-Icons- Mkos-Big-Sur-Transparent-Panel
-Splash Screen- Lain for Plasma6
-Terminal- Konsole

### Widgets

-Desktop Indicator
-Catwalk
-Modern Clock
-Panel Colorizer
-PlasMusic Toolbar
