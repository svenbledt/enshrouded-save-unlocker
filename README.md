# Save Unlocker — Enshrouded character save editor

A native Windows editor for your **Enshrouded** character save (`character*.ksd`).
It only makes edits the game itself allows ("legit edits"), so the game loads the
result as if you had played it. **World saves are never touched.**

## Download

**[⬇ SaveUnlocker-0.1.2.zip](https://github.com/svenbledt/enshrouded-save-unlocker/raw/main/SaveUnlocker-0.1.2.zip)** · Windows 10/11 (64-bit)

Unzip anywhere and run `SaveUnlocker.exe`. Your Steam Cloud saves and local saves
(`%USERPROFILE%\Saved Games\keen games\Enshrouded`) are detected automatically — if
you have both, all of them are listed.

## Virus scan

Both files are unmodified build output and scan clean on VirusTotal (0 detections):

| File | VirusTotal | SHA-256 |
|------|------------|---------|
| `SaveUnlocker.exe` | [0 / 71 — clean](https://www.virustotal.com/gui/file/663eee4a1d9f44836e763a8fbb9b3ac6f8e09a46204c734a065d6e79c35b4425) | `663eee4a1d9f44836e763a8fbb9b3ac6f8e09a46204c734a065d6e79c35b4425` |
| `SaveUnlocker-0.1.2.zip` | [clean](https://www.virustotal.com/gui/file/da4a0383ada7b2ccd925b8f376fabfbafd6207d8067570f9e218c2da4c14cfbe) | `da4a0383ada7b2ccd925b8f376fabfbafd6207d8067570f9e218c2da4c14cfbe` |

To verify a download yourself:

```powershell
Get-FileHash .\SaveUnlocker-0.1.2.zip -Algorithm SHA256
```

## What it does

- Level & XP (up to the cap)
- Skill tree: buy/refund ranks, respec, and apply build presets (Barbarian, Archer,
  Assassin, Healer, Mage) — presets show their path on the tree
- Skill points (Elixir Wells & Shroud Roots), fog of war, item discovery
- Recipe unlocks (world-bound recipes shown read-only)
- Inventory: backpack, action bars, equipment, bags, item level/rarity/upgrades/gems

Enshrouded must be installed (the editor reads item names, icons, the skill tree and
the map from the game). **Close the game before saving** — the editor refuses to write
while Enshrouded is running, and keeps a backup of every save it replaces.

## Disclaimer

Fan-made tool, not affiliated with or endorsed by Keen Games. Enshrouded is a
trademark of its owner. Use at your own risk — keep your backups.
