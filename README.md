# Stalker Cursor Theme for Linux

A port of the **Stalker** Windows cursor theme to Linux.  
Works on **Wayland** and should work on **X11**.

## Variants

| Theme | Arrow |
|-------|-------|
| **Stalker** | Animated |
| **Stalker2** | Static |

Both variants are identical for all other cursors.

## Sizes

Each cursor file contains multiple sizes:  
**24 · 28 · 32 · 40 · 48 px**

To change the size: choose a different cursor and its size, Stalker theme will inherit previously set size.

## Installation

### Option A — Download ZIP from GitHub
```bash
unzip stalker_themes.zip -d ~/.local/share/icons/
```

### Option B — Clone repository
```bash
git clone https://github.com/Urf1st/Stalker_cursor_theme
cd Stalker_cursor_theme
mv Stalker Stalker2 ~/.local/share/icons/
```

Then apply the theme:

**KDE Plasma**  
System Settings → Appearance → Cursors → select Stalker or Stalker2

**GNOME**  
```bash
gsettings set org.gnome.desktop.interface cursor-theme 'Stalker'
gsettings set org.gnome.desktop.interface cursor-size 32
```
Or using Tweaks.

## Notes

- Cursors not present in the original Windows theme (hand, links, etc.) fall back to the default arrow of each variant — animated in Stalker, static in Stalker2.
- Original Windows theme authored by its respective creator. This is a Linux port only.

## Credits

Conversion: `win2xcur` · Resizing: `xcursorgen` + `Pillow`
