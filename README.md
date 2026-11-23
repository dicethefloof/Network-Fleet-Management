# Network Fleet Management (NFM)

**Public preview 0.1** · Subway Builder mod · Windows x64

Network Fleet Management expands how players manage trains, buses, yards, and services in Subway Builder. It adds mixed-fleet management and tools for scheduling, tracking, equipment identification, and transit operations.

> **Version note:** The public GitHub release is labeled **0.1**. The supplied mod package still identifies its internal development version as **1.0.5 WIP**, and targets **Subway Builder 1.8.0**. This is an early preview, not a fully verified stable release.

## What is included

- Fleet Manager and eligible mixed-fleet configuration
- Bus scheduling, rail timetable, and tracking interfaces
- Fleet identification and model-specific car numbering improvements
- Yard-based operating workflows and infrastructure compatibility rules
- Expanded rolling-stock configurations, including Light Rail and Light Metro
- Installer and rollback tools for supported Windows Steam installations

Some advanced operations, including full automatic yard returns, certain consist behaviors, and long-session stability, remain unverified. The existence of a menu or code path is not proof of successful physical operation in-game.

## Installing the public package

1. Download the **public-only ZIP** from the repository's **Releases** page when it has been uploaded.
2. Close Subway Builder and extract the archive.
3. Run **Install NFM.cmd** from the extracted folder.
4. In Subway Builder, open **Settings → Advanced → Mod Manager**, enable **Network Fleet Management Mod**, and restart.
5. Open a city and use the Fleet Manager toolbar button. Normal operations should not require enabling the optional manual-controls switch.

For rollback, close the game and run **Rollback NFM.cmd**. The installer must recognize a supported game archive; do not bypass compatibility checks. Back up important saves before installing a preview mod.

## Public vs. private build

Only the **public redistribution-eligible NFM package** belongs in this repository. **Do not upload private development builds, NYCT or MultiLevel third-party recordings, or private sound references.**

The public package includes a credited public-domain Keikyu GTO recording embedded in the mod; see [audio attribution](ATTRIBUTION_AND_AUDIO.txt). The bundled Python runtime carries its own license in the distribution ZIP.

## Compatibility and limitations

- Target game: **Subway Builder 1.8.0 (verified Steam archive)**
- Platform: **Windows x64**
- Public release label: **0.1**
- Internal mod version: **1.0.5 WIP**

This project is community-developed and is not an official Subway Builder release. Compatibility with future game updates is not guaranteed.

## Rights

This repository does not grant a license to redistribute Subway Builder's proprietary files or third-party materials. No blanket open-source license has been applied to the project at this stage.
