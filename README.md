# SmurfTune - Releases

## What is SmurfTune?

This is a handling.meta generator for FiveM addons and story-mode replaces. GTA does not use hp or 0–100 - it uses a handling item (mass, drive force, grip, brakes, top speed in m/s). SmurfTune fills that file from the real vehicle, then clamps it so the car still plants on a pad in Los Santos.

---

## Download & install

1. Open **[Releases](https://github.com/SmurfCutoms/SmurfTune/releases/latest)**
2. Download and installer `SmurfTune.exe`
3. Run the installer and follow the prompts

**Requirements:** Windows 10/11 (64-bit).

> Windows may warn that the app is unsigned. Choose **More info → Run anyway** if prompted. The project is not code-signed yet.

---

## How to drop this in GTA V

1. **Addon / FiveM:** put the file at `data/handling.meta` and make sure `handlingName` matches the vehicle spawn name.
2. **Replace an existing car:** paste the `<Item>` over that vehicle's block in `handling.meta` - keep the original `handlingName` if you are swapping a vanilla slot.
3. Display units (km/h ↔ mph) never change the meta. Speed in the file is always GTA m/s.

#### `handling.meta` - File Locations

| Vehicle Type | File Location |
|---|---|
| **Vanilla / Replace** | `mods/update/update.rpf/common/data/handling.meta` |
| **Add-on Vehicles** | `mods/update/x64/dlcpacks/DLCPACKNAME/data/handling.meta` |

---

## Support

- Website: [smurfcustoms.co.uk](https://smurfcustoms.co.uk)  
- Discord: [discord.smurfcustoms.co.uk](https://discord.smurfcustoms.co.uk)  
- Email: [info@smurfcustoms.co.uk](mailto:info@smurfcustoms.co.uk)

---

© 2026 Smurf Customs - All rights reserved.  
SmurfTune is proprietary software. Redistribution, modification, or reverse engineering is not permitted.
