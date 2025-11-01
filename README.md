# ChildrenBedtimeStories_MVP

Simple MVP for a children’s bedtime stories service.
This repo contains story scripts, sample audio, a tiny frontend, and notes for the MVP.

## Goal
Provide short bedtime stories that can be played in-browser. Stories can be narrated by a parent-uploaded audio file or a TTS-generated voice.

## Repo structure
- `README.md`            → this file
- `docs/`                → product notes, requirements
- `backend/`             → (future) server/API code
- `frontend/`            → static website (index.html)
- `story_scripts/`       → story text files (.md)
- `voice_samples/`       → (private) parent audio uploads
- `audio_generated/`     → generated mp3 files (for MVP keep small)
- `tests/`               → test cases

## How to run (MVP - static)
1. Add 1–2 MP3 files to `audio_generated/` (e.g. `story1.mp3`, `story2.mp3`).
2. Edit `frontend/index.html` to point to correct filenames (defaults already set).
3. Enable GitHub Pages for this repo (Settings → Pages → deploy `main` branch / root).
4. Open the GitHub Pages URL on your tablet and test playback.

## Next steps (after MVP)
- Add simple admin page to upload voice files and generate TTS.
- Add backend to manage job queue for TTS generation and secure storage.
- Implement user accounts and subscription/monetization.

## Notes / Privacy
- Keep `voice_samples/` private (do not commit private voice files to public repo).
- For demo audio, use short files (<2 MB) while testing.

## License
MIT (suggested) — change as needed.
