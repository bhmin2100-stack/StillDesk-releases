# StillDesk

Windows desktop tiles for hierarchical tasks, daily calendar events, and quick search.

## Download
Download the EXE from [Releases](https://github.com/bhmin2100-stack/StillDesk-releases/releases/latest).
Windows x64, Windows 10 22H2 or later, internet, and App Installer (winget) are required.

At the end of setup, run **Connect PowerToys and Everything**. Missing dependencies are downloaded using winget. Existing installs are reused. Extension registration requires Windows Developer Mode and may request administrator approval. Organization policies may prevent integration.

Alt+Space opens Command Palette. Search files or tasks directly; `+ task title` adds a task.

The app automatically checks this repository for new releases and downloads verified updates. This release is unsigned, so installation requires confirmation. Disable automatic checks in Settings. Tasks and settings stay in `%LOCALAPPDATA%\StillDesk` when updating or uninstalling.

If integration fails, see `%LOCALAPPDATA%\StillDesk\setup-error.txt` and retry **Connect PowerToys and Everything** from the Start menu.

This repository contains release assets; the dashboard source is maintained separately. This is not an official Microsoft or voidtools product.

## Extension source
The modified EPL-2.0 extension and shared bridge source are included in the installer under ThirdParty/EverythingInline-source.zip and as a release asset. See third-party-notices.txt in the release. Dashboard application source is not included.

## Company tile starter kit (1.1)
Download [the company starter ZIP](https://github.com/bhmin2100-stack/StillDesk-releases/releases/download/v1.1.0/StillDesk-CompanyWorkspace-Starter-1.1.zip), which includes the installer, mock providers, source templates, and AI_HANDOFF.md. It contains eight tile frames and an optional calendar feed showing DAY / SW / GY worker names. Real company connectors are unimplemented; no real company credentials or data are included. The timeline remains a separate dashboard feature.
