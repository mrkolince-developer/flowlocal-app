# My Voice — Downloads

This repo hosts **only signed release builds** of My Voice, a local-first
voice dictation app (Windows + Android). Source code is private.

## Latest release: v1.0.0 (Windows + Android)

Grab your platform's build from the
[Releases page](https://github.com/mrkolince-developer/flowlocal-app/releases/latest):

- **Android**: `My-Voice-1.0.0-arm64.apk` — install directly (allow
  "unknown sources" if prompted), or update over a previous install.
- **Windows**: `My.Voice_1.0.0_x64-setup.exe` (installer, recommended) or
  `My.Voice_1.0.0_x64_en-US.msi`.

## First run

1. Open the app — the first account you create becomes the admin.
2. Download a whisper model from the model list.
3. Tap the in-app **?** button any time for the full instruction manual
   (setup, the floating bubble, cloud transcription, troubleshooting).

The floating bubble (drag it anywhere; Enable/Disable in the app) works
the same way on both platforms: click/tap to record, click/tap to stop
and transcribe, click/tap again to copy.

Everything runs locally by default. Cloud transcription/cleanup are
optional and off by default — every account configures its own provider
and API key, and has its own private dictation history. Only account
management (creating/removing users) is admin-only.
