<div align="center">

# Codex Satanas
### Authentic Historical Occult & Full Crimson Theme for Discord

[English](README.md) • [Français](README.fr.md)

<br/>

[![Version](https://img.shields.io/badge/version-12.0.0-960816?style=flat-square)](https://github.com/zitk9/Codex-Satanas/releases)
[![Author](https://img.shields.io/badge/author-!deadcow.ghw-160203?style=flat-square)](https://discord.gg/cdcleak)
[![Discord](https://img.shields.io/badge/discord-discord.gg%2Fcdcleak-cc0a1d?style=flat-square)](https://discord.gg/cdcleak)
[![Clients](https://img.shields.io/badge/clients-Vencord%20|%20Vesktop%20|%20BetterDiscord-160203?style=flat-square)](#compatibility)
[![License](https://img.shields.io/badge/license-MIT-2b0408?style=flat-square)](LICENSE)

<br/>

![Codex Satanas - Home View](assets/discord_main.png)

</div>

---

## Overview

Codex Satanas is an open-source Discord theme built around deep arterial reds and pure obsidian dark tones. It cleans up Discord's default washed-out grey palette and replaces generic AI artwork with high-resolution historical woodcuts and engravings from the 16th and 19th centuries:

- **Stanislas de Guaita (1897)**: *La Clef de la Magie Noire* (Sigil of Baphomet with original Hebrew lettering).
- **Éliphas Lévi (1856)**: *Dogme et Rituel de la Haute Magie* (The Sabbatic Goat).
- **Grimorium Verum (1517)**: The complete Sigil of Lucifer.

Everything is rendered natively through CSS and embedded vector/WebP filters for performance, with zero impact on client responsiveness.

---

## Key Changes

- **Consistent Color System**: Every single Discord token (including the 2026 visual refresh variables) mapped to arterial crimson (`#ff172b`), blood red (`#cc0a1d`), and dark clot (`#3d050b`).
- **Clean Controls**: Compact pill-shaped buttons for window actions (minimize, maximize, close), soundboard, screen share, and mute/deafen controls without distorted borders.
- **Voice Grid Support**: Custom participant cards with dark red glass backing, active speaker highlight, and Baphomet watermark.
- **Embedded Typography**: Includes *Cinzel Decorative*, *UnifrakturMaguntia*, *Cormorant Garamond*, and *JetBrains Mono*.
- **Integrated Addons**: Native styling for Vencord extensions, Spotify playback bar, and server tags.

---

## Compatibility

Codex Satanas uses standard CSS variables and BetterDiscord/Vencord theme headers. It works on any client or extension that supports custom CSS injection:

| Client | Status | Installation Method |
| :--- | :---: | :--- |
| **Vencord** (Desktop) | Supported | One-click Online Theme URL or local `.theme.css` |
| **Vesktop** (Linux / Win / macOS) | Supported | One-click Online Theme URL or local `.theme.css` |
| **BetterDiscord** | Supported | Drop `.theme.css` into the themes folder |
| **Equicord** | Supported | Online Theme or local folder |
| **Legcord** | Supported | Custom CSS panel |
| **ArmCord** | Supported | Custom CSS panel |
| **Dorion** | Supported | Custom CSS panel |
| **Discord Web** (Chrome / Firefox / Brave) | Supported | Stylus extension or Vencord Web |

---

## Installation

### Vencord / Vesktop (Online Theme - Recommended)

1. Open Discord Settings > **Vencord** (or **Vesktop**) > **Themes**.
2. Paste this link into the **Online Themes** field:
   ```text
   https://raw.githubusercontent.com/zitk9/Codex-Satanas/main/codex-satanas.theme.css
   ```
3. Press Enter. The theme will apply immediately and receive updates automatically.

---

### BetterDiscord / Local Installation

1. Download [`codex-satanas.theme.css`](https://raw.githubusercontent.com/zitk9/Codex-Satanas/main/codex-satanas.theme.css).
2. Open Discord Settings > **Themes** (under BetterDiscord or Vencord).
3. Click **Open Themes Folder**.
4. Put `codex-satanas.theme.css` into that directory:
   - **Linux**: `~/.config/BetterDiscord/themes/` or `~/.config/Vencord/themes/`
   - **Windows**: `%appdata%\BetterDiscord\themes\` or `%appdata%\Vencord\themes\`
   - **macOS**: `~/Library/Application Support/BetterDiscord/themes/`
5. Turn on the toggle switch in your theme list.

---

### Browser (Discord Web via Stylus)

1. Install the [Stylus extension](https://add0n.com/stylus.html) on your browser.
2. Open Stylus > Create a new style for `discord.com`.
3. Copy the full content of [`codex-satanas.theme.css`](codex-satanas.theme.css) and paste it.
4. Save the style.

---

## Customization

You can tweak the main red hues directly from the root variables:

```css
:root {
  --crimson-bright: #ff172b;  /* Bright arterial red */
  --crimson-wet:    #cc0a1d;  /* Pure crimson */
  --crimson-artery: #960816;  /* Deep red */
  --crimson-clot:   #3d050b;  /* Dark coagulated red */
  --crimson-abyss:  #0d0102;  /* Obsidian black base */
}
```

---

## Community & Contact

- Author: `!deadcow.ghw`
- Discord: [discord.gg/cdcleak](https://discord.gg/cdcleak)
- Report bugs or submit pull requests directly through GitHub Issues.

---

## License

MIT License. See [LICENSE](LICENSE) for details.
Historical engravings are in the public domain.
