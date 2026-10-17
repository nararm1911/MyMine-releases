# MyMine — releases

Public download channel for **MyMine** (geological 3D modelling, Windows + macOS).
This repository contains **binaries only**; the source code lives in a private repository.

- Installers and auto-update files are attached to each release under **Releases**.
- `latest.json` in the latest release is what installed copies of MyMine poll to find new versions
  (Tauri updater, signed with the MyMine release key).

| Platform | File |
|---|---|
| Windows | `MyMine_<version>_x64-setup.exe` (NSIS, used by the updater) · `MyMine_<version>_x64_*.msi` |
| macOS (universal, unsigned test builds) | `MyMine_<version>_universal.dmg` · `MyMine_universal.app.tar.gz` (used by the updater) |
