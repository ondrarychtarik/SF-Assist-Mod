# SF Assistant — Shakes & Fidget bot (SF bot / S&F bot)

> ⚠️ **Unofficial Personal Fork**  
> This is a **personal, non-maintained fork** of the original SF Assistant.  
> It exists **only for my private testing and experimentation**.  
> **Do not expect support, updates, or long-term maintenance.**  
>  
> All credit for the original project goes to **the-marenga** and the contributors of SF Assistant and sf-api.

[<img src="https://storage.ko-fi.com/cdn/kofi3.png?v=3" height="20" alt="Buy me a coffee">](https://ko-fi.com/senseiissei)

An automation assistant for Shakes & Fidget that streamlines your daily routine with smart, safe defaults and a smooth, modern UI.

## About

SF Assistant is a lightweight automation companion for Shakes & Fidget. It runs the right task at the right time, prioritizes expedition rewards the way you want, and avoids spending sandwatches/glasses unless you explicitly allow it. With event-driven updates, multi-account support, and a clean dark theme, it keeps your daily routine fast and fuss-free across accounts.

Also known as: SF bot, S&F bot, Shakes and Fidget bot, Shakes & Fidget bot, Shakes&Fidget bot.

> Note: S&F has introduced rate limiting that impacts manual server-wide crawling. SF Assistant focuses on in-game automation and quality-of-life features rather than full-server crawls.

## Search keywords

shakes and fidget bot, shakes & fidget bot, sf bot, s&f bot, shakes and fidget automation, shakes & fidget automation, sf automation, sf automation bot, s&f automation bot, shakes fidget bot

## Highlights

- Primary task exclusivity: Only one of Expeditions, Tavern, or City Guard runs at a time to avoid conflicts and waste.
- Expedition reward priority: Choose between sensible presets (default: Mushrooms > Gold > Eggs) to guide automation decisions.
- Safety first: Sandwatches/glasses are off by default. Explicit toggles are available for Tavern and Expeditions.
- Event-driven UI: No periodic refresh timers—snappy and low-flicker updates.
- Custom Charcoal/Orange theme: Clean dark aesthetic with an accent; theme picker still supported.
- Handy toggles: A lightning icon in the Expeditions header quickly enables/disables auto-expeditions.
- Multi-account aware: Per-character, per-server settings are stored when you log in with “Remember me”.

## What it automates

SF Assistant can assist with:

- Tavern: Quest handling, optional beer purchase via mushrooms (within your set budget), optional glasses usage when enabled.
- Expeditions: Reward-aware expedition selection, optional glasses usage, and quick lightning toggle in the UI.
- Dungeons, Pets, Guild: Optional automation toggles for routine checks and fights where applicable.
- Side-actions: Opportunistic actions can run while a primary task is active, where safe and available.

The app enforces that only one primary activity (Tavern, Expeditions, City Guard) runs at any moment to prevent conflicts.

## UI overview

- Automation page
  - Automations: Top-level toggles for battle, lure, tavern, expeditions, dungeons, pets, and guild.
  - Strategy: Select your mission strategy for quests.
  - Expeditions section: Includes a header lightning toggle, a “Use glasses to skip waits” safety toggle, and a “Reward priority” selector.
  - Tavern options: “Buy beer with mushrooms” and “Use glasses to skip waits” toggles.
  - Mushroom budgets: Sliders for daily beer, dungeon skip, and pet skip caps.

## Installation

SF Assistant is a Rust application and can be built from source on Windows, macOS, or Linux.

Prerequisites:
- Rust toolchain (stable)

Build from source:

```powershell
# Windows PowerShell
cargo build --release
