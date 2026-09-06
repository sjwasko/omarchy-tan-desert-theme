# Tan Desert — an Omarchy theme

[![Sponsor](https://img.shields.io/badge/Sponsor-%E2%9D%A4-db61a2?logo=githubsponsors&logoColor=white)](https://github.com/sponsors/sjwasko)
[![Buy me a coffee](https://img.shields.io/badge/Buy%20me%20a%20coffee-ffdd00?logo=buymeacoffee&logoColor=black)](https://buymeacoffee.com/sutibu)

**Retro amber terminal glow · Golden hour desert palette**

A warm, earthy Omarchy theme inspired by the golden-hour desert landscape of Monument Valley. Terminal text glows in retro amber against a deep, semi-transparent tan-brown backdrop.

![Tan Desert preview](preview.png)

## Palette

| Role | Hex | Description |
|------|-----|-------------|
| Background | `#2D1B14` | Deep warm earth — desert canyon shadow |
| Foreground | `#E8B065` | Retro amber terminal glow |
| Accent | `#D4834A` | Burnt orange — sunlit sandstone |
| Bright yellow | `#F0C674` | Bright amber — terminal highlight |
| Selection | `#E8B065` | Matches foreground for high contrast |

### ANSI Color Map

| Index | Color | Hex | Vibe |
|-------|-------|-----|------|
| 0 | Black | `#1A1410` | Deepest canyon shadow |
| 1 | Red | `#C75B39` | Terracotta / desert rust |
| 2 | Green | `#7A9A4C` | Sage / palo verde |
| 3 | Yellow | `#D4A050` | Warm amber sunlight |
| 4 | Blue | `#6A8BA0` | Distant mountain haze |
| 5 | Magenta | `#9C6B7A` | Desert dusk lavender |
| 6 | Cyan | `#6B9A8A` | Agave green |
| 7 | White | `#D4C5B0` | Sandy parchment |
| 8 | Bright black | `#3A2C22` | Dark bark |
| 9 | Bright red | `#E8794D` | Vivid terracotta |
| 10 | Bright green | `#8DB85C` | Vibrant sage |
| 11 | Bright yellow | `#F0C674` | **Retro amber glow** |
| 12 | Bright blue | `#7DA8C0` | Clear desert sky |
| 13 | Bright magenta | `#B88094` | Desert rose bloom |
| 14 | Bright cyan | `#88C4B4` | Bright agave |
| 15 | Bright white | `#EDE0D0` | Sunlit sand |

## Features

- **Retro amber text** — ANSI bright-yellow (`#F0C674`) creates a warm CRT-like terminal glow
- **Semi-transparent windows** — Terminal opacity at 82% shows your wallpaper through a warm brown desert filter
- **16-color cohesive palette** — Every color is drawn from the desert landscape: warm terracotta, sage, agave, mountain-haze blue, dusk lavender
- **Deep enough for dark mode, warm enough to feel alive** — never cold or sterile
- **Fully themed** — Waybar, Mako, Hyprland, Kitty, Foot, Alacritty, Ghostty, btop, SwayOSD, Neovim, VSCode

## Inspiration

Based on a photograph of desert buttes at golden hour — warm orange sandstone, purple-cool shadows in the crevices, distant mountain haze, and the unmistakable amber quality of light just before sunset.

## Installation

```bash
# Install from this repo
omarchy-theme-install git@github.com:sjwasko/omarchy-tan-desert-theme.git

# Or clone and copy manually
git clone https://github.com/sjwasko/omarchy-tan-desert-theme.git
cp -r omarchy-tan-desert-theme ~/.config/omarchy/themes/tan-desert/

# Activate
omarchy theme set tan-desert
```

## Files

| File | What it configures |
|------|--------------------|
| `colors.toml` | Core 16-color palette (the engine of the theme) |
| `kitty.conf` | Kitty terminal — retro amber + 82% opacity |
| `foot.ini` | Foot terminal — same palette + alpha=0.82 |
| `alacritty.toml` | Alacritty — same palette + window opacity |
| `ghostty.conf` | Ghostty — same palette + bg opacity |
| `hyprland.conf` | Hyprland — border colors, window opacity, shadows |
| `waybar.css` | Waybar CSS variables (base styling from Omarchy defaults) |
| `swayosd.css` | On-screen display styling |
| `mako.conf` | Notification daemon styling |
| `btop.theme` | System monitor colors |
| `chromium.theme` | Browser chrome accent color |
| `neovim.lua` | Neovim colorscheme reference |
| `vscode.json` | VSCode colorscheme reference |
| `preview.png` | Theme preview screenshot |
| `unlock.png` | Hyprlock branding bar |
| `backgrounds/` | Wallpaper images |

## License

MIT — use it, share it, remix it.