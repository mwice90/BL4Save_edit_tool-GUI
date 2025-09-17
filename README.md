# BL4Save_edit_tool-GUI
GUI save editor for Borderlands 4. Safely edits YAML values (Level, Cash, Eridium, Skill Points, Tokens) and re-packs saves via official CLI. Preserves structure to avoid corruption. Includes SDU upgrades and optional CLI helper. Coded By XaveN...(fürOPA WO.WI)
# BL4Save_edit_tool-GUI

A GUI-based save editor for **Borderlands 4** that performs precise YAML edits and safely re-packs saves using the official CLI.

---

## 🧩 Purpose

- Perform **surgical edits** to Borderlands 4 save files (.sav/.yaml)
- Preserve YAML structure, tags, and line endings to avoid corrupted saves
- Seamlessly integrate with the official `bl4-crypt-cli` for proper repacking

---

## ✨ Features

- Edit key values: `Level`, `Cash`, `Eridium`, `Skill Points`, `Spec Tokens`, `Echo Tokens`
- SDU upgrades: `Backpack`, `Bank`, and optionally `Ammo` via non-destructive text patches
- GUI workflow: `Load Info → Edit Values → Write .sav`
- Optional CLI helper for advanced users

---

## 🛠 Requirements

- **Game:** Borderlands 4 (Steam version)
- **CLI Tool:** `bl4-crypt-cli.exe` (must be placed next to the GUI or selected via “Find CLI”)
- **SteamID64:** Your 17-digit Steam ID (e.g., `7656119...`) — enter manually or via `steamid.txt`

---

## 📦 Installation

### Vortex (Mod Manager)
- Type: Utility tool (not a gameplay mod)
- Deploy the archive as a tool or extract manually
- Ensure both `bl4-save-tool-gui.exe` and `bl4-crypt-cli-*.exe` are in the same folder

### Manual
- Extract to any folder (e.g., `C:\Tools\BL4SaveTool`)
- Place `bl4-crypt-cli-*.exe` in the same directory
- Optionally create `steamid.txt` containing your SteamID64

---

## 🚀 Usage (GUI)

1. **Input:** Select a `.sav` or `.yaml` file
2. **Output:** Choose a target `.sav` file
3. **SteamID:** Enter manually or use `steamid.txt`
4. **Find CLI:** Select your `bl4-crypt-cli-*.exe`
5. **Load Info:** Preview current save values
6. **Edit:** Modify Level, Cash, Eridium, SkillPts, SpecTokens, EchoTokens
7. **Write .sav:** Save the edited file in correct format

---

## 🔒 Safe Editing Workflow

- Close the game and temporarily disable Steam Cloud
- Backup original save:  
  `...\Saved\SaveGames\<SteamID64>\Profiles\client\`
- Replace the file (e.g., `1.sav`) with the edited version
- Launch the game and verify changes

---

## 🧯 Troubleshooting

- **Corrupted save:** Always use the official `bl4-crypt-cli` via “Find CLI”
- **Wrong SteamID:** Decryption/encryption requires correct SteamID64
- **Cloud overwrites:** Disable Steam Cloud during testing, re-enable after verification

---

## 👤 Credits

- **Author:** XaveN (fürOPA WO.WI)
- **Tooling:** Uses the official `bl4-crypt-cli` for packing
- **Thanks:** Community testers and feedback providers

---

## 📜 Permissions

- Personal use allowed
- Do **not** redistribute modified versions of the official CLI
- When sharing this tool, please credit:  
  `Coded By XaveN...(fürOPA WO.WI)`

---

## 📝 Changelog

- **v1.0:** Initial GUI release with surgical editing and CLI integration  
- **v1.1:** UI improvements, Help dialog, safer line-ending handling
