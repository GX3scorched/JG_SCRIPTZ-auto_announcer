# Auto Announcer (ESX) - made by JG_SCRIPTZ

## What it does
- Automatically posts configured announcements to the in-game chat on a loop.
- Each announcement can have its own delay (in seconds) before the next announcement.

## Installation
1. Place the folder `auto_announcer_jg_scriptz` into your server `resources` folder.
2. Ensure you have `es_extended`, `ox_lib`, and `ox_target` resources installed and started.
3. Add `ensure auto_announcer_jg_scriptz` to your `server.cfg`.

## Configuration
- Edit `config.lua` to change announcements, delays, and prefix.
- Example:
  ```lua
  Config.Announcements = {
      { text = "Welcome to the server!", delay = 300 },
      { text = "Remember to follow the rules.", delay = 600 }
  }
  ```

## Notes
- Runs automatically when the resource starts — no commands needed.
- Credit: JG_SCRIPTZ
