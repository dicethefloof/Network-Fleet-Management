# Network Fleet Manager (NFM)

**Network Fleet Manager 1.0.0 Beta** · Subway Builder mod · Windows x64

Network Fleet Manager expands how players manage trains, buses, yards, and services in Subway Builder. It adds mixed-fleet management and tools for scheduling, tracking, equipment identification, and transit operations.

> **Version note:** The mod is **1.0.0 Beta** (`1.0.0-beta` in its manifest). Legacy `v105` worker protocol identifiers and historical changelog entries remain for save compatibility. **No GitHub binary release has been published yet.** Automatic rail dispatch and long-session stability still require live verification.

## What is included

- Fleet Manager and eligible mixed-fleet configuration
- Bus scheduling, rail timetable, and tracking interfaces
- Fleet identification and model-specific car numbering improvements
- Yard-based operating workflows and infrastructure compatibility rules
- Expanded rolling-stock configurations, including Light Rail and Light Metro
- Installer and rollback tools for verified Windows game archives; Steam is detected automatically and other install locations can be specified manually

The latest targeted report found a Tokyo train and an R142A remaining parked in automatic rail-mixing scenarios; the specific hold conditions were not established. Full automatic yard returns and long-session stability remain unverified. The existence of a menu or code path is not proof of successful physical operation in-game.

## Installing Network Fleet Manager

1. Download the **owner-signed Network Fleet Manager 1.0.0 Beta Windows ZIP** from this repository's **Releases** page once an official release is published. Do not install an unsigned owner preparation kit.
2. Close Subway Builder and extract the archive.
3. Run **Verify Network Fleet Manager.cmd** to verify the official release signature and all files, then run **Install NFM.cmd** from the extracted folder. Steam installs are auto-detected. For another Windows distribution, point the installer at the folder containing `resources/app.asar`, e.g. `"Install NFM.cmd" --game-dir "C:\\Path\\To\\Subway Builder"` in Command Prompt. The game archive must still match one of the hashes the installer supports.
4. In Subway Builder, open **Settings → Advanced → Mod Manager**, enable **Network Fleet Manager**, and restart.
5. Open a city and use the Fleet Manager toolbar button. Normal operations should not require enabling the optional manual-controls switch.

For rollback, close the game and run **Rollback NFM.cmd**. The installer must recognize a supported game archive; do not bypass compatibility checks. Back up important saves before installing a beta mod.

## Release contents and private files

Only the **public redistribution-eligible NFM package** belongs in this repository. **Do not upload private development builds, NYCT or MultiLevel third-party recordings, or private sound references.**

The current redistribution package uses **Subway Builder's native audio only**. It includes no custom NYCT, MultiLevel, or other private recordings and no proprietary game archive. See [audio attribution](ATTRIBUTION_AND_AUDIO.txt). The bundled Python runtime carries its own license in the distribution ZIP.

## Compatibility and limitations

- Target game: **Subway Builder 1.8.0**
- Intended Windows distribution support: **Steam and direct purchases from the game's website**
- Verified installer compatibility: **Specific Subway Builder 1.8.0 Steam `app.asar` hashes only**. A website-purchased build may work if its archive is identical; different builds require separate verification and installer support.
- Platform: **Windows x64** (not a guarantee of support for every Windows OS release or 32-bit Windows)
- Public release version: **1.0.0 Beta** (not yet published)
- Internal manifest version: **1.0.0-beta**

## Official release signing

The owner is preparing **Ed25519 signed releases** to let players verify that an NFM package is authentic. The private signing key and its passphrase remain **on the owner's own PC**, never in this repository or a downloadable ZIP. The installer verifies the signed file inventory before installing, and fails safely if files have changed.

**The signing setup is still pending the owner's personal key generation and signing. No signed binary is published yet.** Once configured, the release page will display the public key's SHA-256 fingerprint, and players should compare it with the installer's verified identity. Signing verifies an authorized distribution; it cannot make client-side JavaScript impossible to inspect or modify.

This project is community-developed and is not an official Subway Builder release. Compatibility with future game updates is not guaranteed.

## Rights

This repository does not grant a license to redistribute Subway Builder's proprietary files or third-party materials. No blanket open-source license has been applied to the project at this stage.
