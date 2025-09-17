Purpose: GUI save editor for Borderlands 4 that performs surgical YAML edits and re‑packs saves safely via the official CLI.
Safety: Preserves structure/tags and line endings to avoid “corrupted save” issues.
Signature: Coded By XaveN...(fürOPA WO.WI)
Features

Surgical edits: Level, Cash, Eridium, Character Skill Points, Spec Tokens, Echo Tokens.
SDU upgrades: Backpack/Bank (and ammo on request) via non‑destructive text patches.
GUI workflow: Load Info → Edit values → Write .sav.
Optional CLI: Includes a small command‑line helper for power users.
Requirements

Game: Borderlands 4 (Steam saves).
bl4-crypt-cli: Place the EXE next to this tool, or select it via “Find CLI”. This ensures the exact packing (zlib + PKCS7 + layout).
SteamID64: Your 17‑digit Steam account ID (e.g., 7656119…), either in the GUI or in steamid.txt.
Install (Vortex)

Type: Utility tool (not a traditional gameplay mod).
Files: Deploy the archive as a tool, or extract to a tools folder and add as a custom tool.
Path: Keep bl4-save-tool-gui.exe and bl4-crypt-cli-*.exe in the same folder for best results.
Install (Manual)

Extract anywhere (e.g., C:\Tools\BL4SaveTool).
Put bl4-crypt-cli-*.exe in the same folder (recommended).
Optionally create steamid.txt with your SteamID64.
Usage (GUI)

Input: Pick a .sav or .yaml.
Output: Set a target .sav.
SteamID: Enter your SteamID64, or have it in steamid.txt.
Find CLI: Click and select your bl4-crypt-cli-*.exe (recommended).
Load Info: Preview values from the save.
Edit: Set Level/Cash/Eridium/SkillPts/SpecTokens/EchoTokens.
Write .sav: Creates the edited save with the correct format.
Safe Editing Workflow

Close the game and temporarily disable Steam Cloud.
Back up your original save: ...\Saved\SaveGames\<SteamID64>\Profiles\client\.
Replace the file (e.g., 1.sav) with the edited one.
Launch the game and verify.

Troubleshooting

Corrupted save: Ensure the GUI is using the official bl4-crypt-cli (use “Find CLI”). Do not alter unrelated YAML content.
Wrong SteamID: Decrypt/encrypt requires the correct owner SteamID64.
Cloud overwrites: Disable Steam Cloud while testing, then re‑enable once verified.
Credits

Author: XaveN (fürOPA WO.WI)
Tooling: Uses the official bl4-crypt-cli for packing.
Thanks: Community testers and feedback providers.
Permissions

Personal use allowed. Do not re‑host modified binaries of the official CLI. Credit “Coded By XaveN...(fürOPA WO.WI)” when redistributing this tool.
Changelog

v1.0: Initial GUI release with surgical editing and CLI integration.
v1.1: UI improvements, Help dialog, safer line‑ending handling.
------ German (Deutsch) ----



------ German (Deutsch) ------

Übersicht

Zweck: GUI‑Save‑Editor für Borderlands 4, der chirurgische YAML‑Änderungen vornimmt und Saves sicher über das offizielle CLI neu verpackt.
Sicherheit: Struktur/Tags und Zeilenenden bleiben erhalten, um “beschädigte Saves” zu vermeiden.
Signatur: Coded By XaveN...(fürOPA WO.WI)
Funktionen

Chirurgische Edits: Level, Cash, Eridium, Charakter‑Skillpunkte, Spezialisierungs‑Tokens, Echo‑Tokens.
SDU‑Upgrades: Rucksack/Bank (und auf Wunsch Munition) via nicht‑destruktive Text‑Patches.
GUI‑Ablauf: Load Info → Werte anpassen → Write .sav.
Optionales CLI: Kleines Kommandozeilen‑Tool für Power‑User.
Voraussetzungen

Spiel: Borderlands 4 (Steam‑Saves).
bl4-crypt-cli: Lege die EXE neben dieses Tool oder wähle sie in der GUI („Find CLI“). So wird exakt im Spiel‑Format verpackt.
SteamID64: 17‑stellige Steam‑ID (z. B. 7656119…), in der GUI oder in steamid.txt.
Installation (Vortex)

Typ: Utility‑Tool (kein klassischer Gameplay‑Mod).
Dateien: Archiv als Tool bereitstellen oder entpacken und als Custom Tool eintragen.
Pfad: bl4-save-tool-gui.exe und bl4-crypt-cli-*.exe im selben Ordner halten.
Installation (Manuell)

Beliebigen Ordner nutzen (z. B. C:\Tools\BL4SaveTool).
bl4-crypt-cli-*.exe in denselben Ordner legen (empfohlen).
Optional steamid.txt mit der eigenen SteamID64 erstellen.
Benutzung (GUI)

Input: .sav oder .yaml auswählen.
Output: Ziel‑.sav setzen.
SteamID: SteamID64 eintragen oder per steamid.txt.
Find CLI: bl4-crypt-cli-*.exe auswählen (empfohlen).
Load Info: Werte aus dem Save anzeigen.
Bearbeiten: Level/Cash/Eridium/Skillpunkte/SpecTokens/EchoTokens setzen.
Write .sav: Erzeugt die bearbeitete Save im korrekten Format.
Sicheres Vorgehen

Spiel schließen und vorübergehend Steam‑Cloud deaktivieren.
Original‑Save sichern: ...\Saved\SaveGames\<SteamID64>\Profiles\client\.
Datei ersetzen (z. B. 1.sav) und im Spiel prüfen.


Beschädigte Save: In der GUI unbedingt das offizielle bl4-crypt-cli nutzen („Find CLI“). Keine fremden YAML‑Teile verändern.
Falsche SteamID: Decrypt/Encrypt benötigt die korrekte Besitzer‑SteamID64.
Cloud‑Überschreibungen: Während des Tests Cloud deaktivieren, danach wieder aktivieren.
Credits

Autor: XaveN (fürOPA WO.WI)
Tooling: Verpackt über das offizielle bl4-crypt-cli.
Dank an alle Tester und Feedback‑Geber.
Rechte

Private Nutzung erlaubt. Modifizierte Versionen des offiziellen CLI nicht weiterverbreiten. Bei Weitergabe dieses Tools bitte “Coded By XaveN...(fürOPA WO.WI)” nennen.
Changelog

v1.0: Erste GUI‑Version mit chirurgischem Edit und CLI‑Integration.
v1.1: UI‑Verbesserungen, Hilfe‑Dialog, sichere Zeilenende‑Behandlung.
If you want, I can also generate a shorter “Vortex field” summary or a separate sticky post template for the Posts tab.