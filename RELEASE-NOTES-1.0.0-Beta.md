# Network Fleet Manager 1.0.0 Beta

**First public Beta — Windows x64 / verified Subway Builder 1.8.0 builds**

NFM expands fleet management with mixed vehicle configurations, bus scheduling, rail timetable planning, automatic roster numbering, independent married-set numbers, vehicle tracking, and a much larger rolling-stock catalog.

## Installation

1. Download `Network-Fleet-Manager-1.0.0-Beta-Windows.zip` from the release's Assets section, not the automatically generated source-code archives.
2. Close Subway Builder, back up important saves, and extract the ZIP.
3. Run `Verify Network Fleet Manager.cmd`. If verification passes, run `Install NFM.cmd` and follow the prompts.
4. Open Subway Builder, go to Settings → Advanced → Mod Manager, enable Network Fleet Manager, and restart.
5. Test on a fresh city and open the Fleet Manager toolbar button.

**No signing key, passphrase, separate Python installation, or developer access is required.** For nonstandard game locations, see the README. To roll back, close the game and run `Rollback NFM.cmd`.

## Included

- Eligible mixed bus and rail fleet selection, shared-yard operating workflows, and compatibility restrictions.
- Bus run scheduling, rail timetables, layover planning, passenger monitoring, vehicle tracking, and service history.
- Automatic sequential fleet numbering from built-in roster ranges, including separate married sets and individual locomotive, coach, cab-car and bus records.
- Expanded bus, heavy metro, commuter, intercity, light rail, light metro and selected Japanese equipment.
- Installer checksums, verified native archive compatibility checks, backups, and rollback.

## Known limitations

This is a Beta, not a stable release. Earlier gameplay tests confirmed bus mixing, but automatic rail departures, full scheduled yard returns and long-session stability still require live verification. The rail catalog synchronization defect has been corrected in code; the previously reported parked Tokyo train and R142A have not been retested live. Some models have missing or exhausted fleet-number ranges. Fully enforced layovers, automatic short-turns, physical consist editing and individual vehicle liveries are not completed features.

Only verified Subway Builder 1.8.0 Windows archives are supported. Subway Builder 1.8.1-rc1 is not supported. Other distributions may require compatibility verification.

## Download integrity

Expected ZIP SHA-256:

```
656dbad8b600240bb5cdeb52b5dfb646430fb63bebe45b5911eb42f0d8ab99c0
```

The installer contains an integrity verifier. Checksums detect corruption or differences from the published archive, not cryptographic authorship.

No custom sound recordings or proprietary game archive are included. Report issues through the repository's Issues page with reproduction steps, game and mod versions, other enabled mods, and relevant logs or screenshots with private information removed.

[Full installation and rollback instructions](https://github.com/dicethefloof/Network-Fleet-Management#install-nfm)
