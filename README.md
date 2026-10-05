# KABA – Offerten & Rechnungen

Downloads of **KABA**, the quote and invoice program of KABA Gartenbau (made by DigiThera L.L.C.). This repository only holds the
installers; the source code is private.

➡ **[Latest version → Releases](../../releases/latest)**

## Deutsch

1. Laden Sie `KABA-Setup-<Version>.exe` und die Datei `KABA-Setup-<Version>.exe.sha256` unter [Releases](../../releases/latest) herunter.
2. Prüfen Sie die Datei (empfohlen). In PowerShell im Download-Ordner:

   ```powershell
   Get-FileHash .\KABA-Setup-<Version>.exe -Algorithm SHA256
   ```

   Der Wert muss genau dem Inhalt der `.sha256`-Datei entsprechen. Wenn nicht: **nicht installieren**, bei DigiThera melden.
3. Doppelklick auf die Setup-Datei. Es sind keine Administratorrechte und keine weiteren Programme nötig.
   Zeigt Windows «Der PC wurde durch Windows geschützt» (die Datei ist noch nicht signiert):
   «Weitere Informationen» → «Trotzdem ausführen», aber nur wenn die Prüfsumme stimmt.
4. Aktualisieren: die neue Setup-Datei einfach über die alte installieren. Ihre Daten bleiben erhalten; KABA kann auch
   selbst nach Updates suchen (Einstellungen → Updates).

## English

1. Download `KABA-Setup-<version>.exe` and `KABA-Setup-<version>.exe.sha256` from [Releases](../../releases/latest).
2. Check it: `Get-FileHash .\KABA-Setup-<version>.exe -Algorithm SHA256` must equal the content of the `.sha256` file.
   If it differs, do not install it.
3. Run the setup (no administrator rights needed). If Windows SmartScreen warns about an unknown publisher (the build is
   not signed yet), choose "More info" → "Run anyway", only after the checksum matched.
4. To update, install the new setup over the old one; your data is kept. KABA can also look for updates itself
   (Einstellungen → Updates).

## Français / Italiano

Téléchargez / Scarica le fichier `KABA-Setup-<version>.exe` et le fichier `.sha256` ; vérifiez / verifica
`Get-FileHash … -Algorithm SHA256` = fichier / file `.sha256`; puis double-clic / poi doppio clic.
