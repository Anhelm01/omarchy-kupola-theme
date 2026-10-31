# ⛪ Kupola Theme for Omarchy

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

A high-contrast dark theme for [Omarchy](https://omarchy.org/) inspired by black & white church architecture photography with vibrant pop-art neon accents.

![Kupola Preview](preview.png)

---

## 🎨 Color Palette

The palette is built around deep monochromatic grays representing stone and overcast skies, contrasted with vibrant neon hot pink accents inspired by stylized church domes.

| Color | Hex | Role |
| :--- | :--- | :--- |
| **Accent / Pink** | `#FF1493` | Primary accent, notifications, focus states |
| **Hot Pink** | `#FF69B4` | Bright accent, directories, links |
| **Background** | `#1A1A22` | Base background |
| **Dark Background** | `#121218` | Panels, status bar background |
| **Darker Background** | `#0C0C10` | Popups, menus, modals |
| **Lighter Background**| `#2E2E3A` | Cards, active tabs, buttons |
| **Foreground** | `#D8D8E0` | Main text (cold white) |
| **Muted** | `#4A4A5A` | Inactive text, borders |
| **Active Border** | `rgba(ff1493ee) rgba(ff69b4ee) 45deg` | Hyprland window gradient |

### Terminal ANSI Colors

| Role | Normal | Bright |
| :--- | :--- | :--- |
| **Black** | `#1A1A22` | `#4A4A5A` |
| **Red** | `#FF1493` | `#FF3EAA` |
| **Green** | `#85C898` | `#A0DCAF` |
| **Yellow** | `#E8A8C0` | `#F0B8D0` |
| **Blue** | `#FF1493` | `#FF69B4` |
| **Magenta** | `#D070B8` | `#E888D0` |
| **Cyan** | `#E890C0` | `#FFB8E0` |
| **White** | `#D8D8E0` | `#E8E8F0` |

---

## 🚀 Installation

### Using the Omarchy CLI (Recommended)

Run the following command in your terminal:

```bash
omarchy theme install https://github.com/Anhelm01/omarchy-kupola-theme.git
```

Omarchy will automatically clone the theme, generate application configs (terminals, btop, hyprland, etc.), and activate the theme with its wallpaper.

---

### Manual Installation

If you prefer to install manually:

1. Clone this repository into your Omarchy themes folder:
   ```bash
   git clone https://github.com/Anhelm01/omarchy-kupola-theme.git ~/.config/omarchy/themes/kupola
   ```

2. Activate the theme:
   ```bash
   omarchy theme set kupola
   ```

3. Restart your terminal if already open:
   ```bash
   omarchy restart terminal
   ```

---

## 🖥️ Supported Applications

Omarchy automatically renders configurations for:
- **Window Manager:** Hyprland (gradient active border `#FF1493` ➔ `#1E90FF`)
- **Terminals:** Foot, Kitty, Alacritty, Ghostty
- **CLI & TUI:** Btop, Fastfetch, Starship, Gum
- **Editors:** Neovim, Helix, VS Code
- **Icons:** Yaru-magenta-dark

---

## 📄 License

MIT License. Copyright (c) 2026 Кратюк Матвей. Feel free to use, modify, and share!
