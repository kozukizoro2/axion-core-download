# AXION CORE Beta v1.0.2

Windows beta release for AXION CORE.

## Important Update Fix

This release fixes the Windows auto-update feed configuration. AXION CORE now uses the GitHub release channel embedded by electron-builder:

- Owner: `axion-core-app`
- Repository: `axion-core-download`

Users on older builds that pointed to the old test update URL may need to install this version manually once. After installing v1.0.2, future updates can be delivered through GitHub Releases.

## Included Builds

- `AXION-CORE-Setup-1.0.2.exe` - normal Windows installer.
- `AXION-CORE-Portable-1.0.2.exe` - portable build for testing without installation.
- `latest.yml` and `.blockmap` - auto-update metadata.

## Current Highlights

- Command Center for storage, server status, pending actions, and library overview.
- Media Organizer for grouped Movies / TV Shows / Anime rename previews.
- Library Planner for mixed-library cleanup with grouped planned changes and undo support.
- Auto Organizer for watching download folders after the main library is configured.
- Convert & Subtitles for MKV remuxing, subtitle cleanup, audio track control, and external subtitle files.
- Media Health Center for library scans, duplicate/conflict review, and repair workflows.
- AXION AI Advisor support with local Ollama recommended and optional cloud AI providers.

## Beta Notes

AXION CORE is still in active Windows beta. Test on a copied folder or a small sample before applying changes to a full production library.

Feedback: support@axioncore.app
