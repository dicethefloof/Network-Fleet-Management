# Network Fleet Manager — 1.0.0 Beta

Network Fleet Manager (NFM) is a fleet and transit operations expansion for Subway Builder. It adds mixed-fleet configuration, equipment numbering, scheduling tools, vehicle tracking, and an expanded vehicle roster.

> **Beta for verified Subway Builder 1.8.0 builds on Windows x64.** Automatic rail departures, full yard returns, and long-session stability still need further gameplay verification.

## Download

Open the [Releases page](https://github.com/dicethefloof/Network-Fleet-Management/releases) and select **Network Fleet Manager 1.0.0 Beta** when available.

Under **Assets**, download **Network-Fleet-Manager-1.0.0-Beta-Windows.zip**.

Do not download GitHub's automatically generated "Source code" ZIP or an older owner signing kit. The Windows ZIP is the installer package.

## Before installing

- You need a compatible Windows x64 installation of Subway Builder **1.8.0**. Only verified game archive builds are supported.
- Close Subway Builder completely and back up your important saves.
- No separate Python installation, signing key, passphrase, developer access, or command-line setup is needed for a standard Steam installation.

## Install NFM

1. Right-click the downloaded ZIP and select **Extract All**.
2. Open the extracted folder. Keep the included files and the `runtime` folder together.
3. Double-click **Verify Network Fleet Manager.cmd** to check the extracted package's integrity.
4. If verification passes, double-click **Install NFM.cmd**. Read the installer output and follow any prompts. Existing NFM installations may require confirmation before replacement.
5. After installation succeeds, start Subway Builder.
6. Go to **Settings → Advanced → Mod Manager**, enable **Network Fleet Manager**, and restart the game.
7. Open a new city first to confirm the game loads and the **Fleet Manager** toolbar button is available. Leave experimental **Enable manual NFM controls** OFF for ordinary service.

If the installer fails, do not ignore its error or bypass its checks. See troubleshooting below.

### Nonstandard Steam library or website purchase

If the installer cannot locate your game, open Command Prompt inside the extracted folder and run:

```cmd
"Install NFM.cmd" --game-dir "D:\Games\Subway Builder"
```

Replace the example directory with your actual game folder (the one containing `resources\app.asar`).

Website-purchased copies are supported only when the game archive matches a verified build. A matching version number alone does not guarantee compatibility.

## Features

- Configure eligible mixed bus and rail fleets, subject to vehicle, infrastructure, and yard compatibility.
- Manage bus runs, rail timetables, layover planning, vehicle tracking, and fleet inventory.
- Assign persistent fleet numbers from built-in operator roster ranges, with separate married-unit, locomotive, coach, and cab-car records.
- Browse an expanded roster of buses, subway trains, commuter rail, intercity equipment, light rail, light metro, and selected Japanese rolling stock.
- Use passenger monitoring, equipment specifications, and track audits.
- Install, upgrade, or roll back using the included Windows tools.

The mod preserves native vehicle IDs. Fleet numbers are in-game roster allocations, not proof that a formation matches an actual historical train. Models without documented ranges, or with exhausted ranges, still need additional roster data.

## Compatibility and known limitations

| Item | Status |
| --- | --- |
| Subway Builder 1.8.0, verified Windows archives | Supported by installer |
| Subway Builder 1.8.1-rc1 and other unverified archives | Not supported |
| Steam | Standard installation auto-detected |
| Website edition | Matching verified archive required |
| macOS / Linux | Not supported by this Windows installer |
| Automatic bus mixing | Observed working in prior gameplay tests |
| Automatic rail mixing / yard returns | Further live testing needed |
| Long-session stability | Not yet verified |
| Individual vehicle wraps, enforced layovers, automatic short-turns, physical consist editing | Incomplete or not included |

The installer performs checksum and archive compatibility checks. These protect against accidental corruption and incompatible patching; they do not prove the authorship of third-party repackaged downloads.

## Rollback

Close Subway Builder and double-click **Rollback NFM.cmd** in the extracted installer folder.

Rollback restores the verified archive and mod files from immediately before the last managed installation, subject to matching backup records. It does not restore a save from an earlier gameplay session. Keep your own save backups.

## Troubleshooting and bug reports

- **Unsupported archive/hash:** Do not force the installer to run. Report your game version and the exact error.
- **Game directory not found:** Use the manual game directory command above.
- **Verification failure:** Re-download the official ZIP and extract into a fresh folder.
- **Fleet Manager missing or city won't load:** Confirm NFM is enabled, restart, and test on a fresh city. If necessary, roll back.
- **Game updates:** Do not reuse this installer against an unverified newer build.

Report bugs through [GitHub Issues](https://github.com/dicethefloof/Network-Fleet-Management/issues). Include the game version, NFM version, other enabled mods, a description of what happened, steps to reproduce, and relevant screenshots or logs. Remove private information before posting logs.

## Release contents

The distribution contains no private sound recordings or proprietary base-game archive. It uses Subway Builder's built-in audio. See [attribution](ATTRIBUTION_AND_AUDIO.txt). The bundled Python runtime includes its license.

NFM is a community-developed mod, not an official Subway Builder release. No blanket open-source license has been granted to NFM.

[Release notes](RELEASE-NOTES-1.0.0-Beta.md)
