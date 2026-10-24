# IV:MP T4 for GTA IV 1.2.0.43 (Complete Edition) — Reference

> **Attribution & ownership notice — read first.**
> IV:MP (IV Multiplayer) is the original work of the **IV-Multiplayer team**
> (official site: <https://www.iv-mp.eu>). This repository is an independent
> documentation/reference page maintained by SENESO. It does **not** claim
> ownership of IV:MP, it is **not** affiliated with the IV-Multiplayer team,
> and it does **not** redistribute the client binaries. Download the client
> from the official sources linked below.

## What this is

IV:MP T4 is an alternative multiplayer modification for Grand Theft Auto IV
(The Complete Edition, patch 1.2.0.43). It lets players run their own servers
and play together, with scripted game modes (Squirrel/Lua scripting base).

- Official site: <https://www.iv-mp.eu>
- ModDB page: <https://www.moddb.com/downloads/ivmp-t4>
- Install guide (video, linked from the archive's README): <https://youtu.be/UoqXLYc67qM>

## Verified archive (downloaded 2026-10-24, from ModDB)

| Field | Value |
|---|---|
| File name | `IV-MP_T4_for_GTA_IV_1.2.0.43.zip` |
| Size | 69,407,328 bytes (66.19 MB) |
| MD5 | `dc29a1313c652f48c23203ad22c6f513` |
| Added on ModDB | 2021-07-08 |
| Target game | GTA IV 1.2.0.43 (The Complete Edition) |

The MD5 above was verified against the downloaded file after extraction.

## Archive contents (46 files, ~82 MB extracted)

Top-level layout inside `IV-MP T4 for GTA IV 1.2.0.43/`:

- `README.TXT` — points to the install-guide video.
- `IV-MP T4 Files/` — the client package, including:
  - `comMP/bin/ClientLauncher.exe`, `ivmpUpdater.exe`, `launcherAssist.dll`
  - `comMP/Client.dll`, `comMP/ClientManager.dll`
  - `comMP/config/` — client config (`config.txt`, `anims.dat`, `favorites.txt`)
  - `comMP/GUI/` — launcher UI assets
  - `comMP/TeamSpeak/` — TeamSpeak plugin (`IVMP-TS.dll`, `ts3client.dll`)
  - `comMP/TBOGT/`, `common/data/`, `TBoGT/`, `TLAD/` — game data files
    (`ivmpvehicles.ide`, `veh-colors.dat`, `*.img`, `*.xml`, `*.dat`)
  - `EFLC.exe`, `LaunchEFLC.exe`, `gta4Browser.exe`, `gtaEncoder.exe`,
    `ivmpGameLauncher.exe`, `bass.dll`, `binkw32.dll`, `clientLibs.dll`,
    `data.dll`, `xlive.dll`, `EFLC install.reg`, `Uninstall-IVMP.bat`

No license file is included in the archive. The binaries are **not** included
in this repository.

## Relation to SENESO/ivmp-platform

This client is kept as a local reference for compatibility testing of
[SENESO/ivmp-platform](https://github.com/SENESO/ivmp-platform) (a separate,
private project) against GTA IV Complete Edition 1.2.0.43. Nothing in this
repository is part of, or a fork of, the IV:MP source code.

## License

The documentation in this repository (this README and any other files
authored by SENESO here) is released under the MIT License — anyone may copy,
use, and share it, with attribution (see `LICENSE`).

IV:MP itself is **excluded**: it remains the property of its original authors.
If you use IV:MP, follow the terms published by the IV-Multiplayer team on
<https://www.iv-mp.eu>.
