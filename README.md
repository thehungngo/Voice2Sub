# Voice2Sub — AI Subtitle Generator for Video & Audio

**Voice2Sub** is a cross-platform desktop app that turns speech from video or audio files into AI-generated subtitles, transcripts and editable text.

It is built for creators, editors, students, educators, podcasters and anyone who needs a private, local-first subtitle workflow on **Windows, macOS and Linux**.

> Generate subtitles from audio and video files with local AI transcription, export to common subtitle/text formats, and keep your media files on your own computer.

## Download

- Website: https://voice2sub.pro.vn/
- Download: https://voice2sub.pro.vn/download
- What's new: https://voice2sub.pro.vn/whats-new

## Key features

- AI subtitle generation from video and audio files
- Local speech-to-text workflow powered by Whisper-style AI models
- Export subtitles and transcripts to common formats such as SRT, VTT, TXT, LRC and CSV
- Support for many recognition languages
- Prompt/context input to improve transcription accuracy for specific content
- Temperature and advanced transcription controls
- Audio Quality Enhancement for difficult or noisy recordings
- Windows, macOS and Linux desktop support
- Optional CUDA acceleration on supported NVIDIA GPUs
- Apple Silicon / Metal-oriented desktop workflow on macOS
- Local-first workflow: no need to upload your private media to a website for transcription

## Why Voice2Sub?

Many transcription tools are either online-only, limited to basic audio files, or designed as generic speech-to-text utilities. Voice2Sub focuses on a dedicated **subtitle generation workflow**:

- Import video or audio
- Configure model, prompt and quality settings
- Generate subtitles/transcripts locally
- Export in formats ready for editing, learning, documentation or content creation

## Release history

Voice2Sub publishes release notes on the official website and mirrors the public version history here for GitHub discovery.

### v1.1.2 — English speech-to-subtitle translation and smoother multilingual experience

**Date:** June 5, 2026
**Status:** Current stable release

Voice2Sub 1.1.2 adds translation from source-language speech into English subtitle files, improves multilingual UI rendering, makes CUDA setup clearer, and updates the subtitle engine for better stability across Windows, Linux, and macOS.

- Translate speech from supported source languages into English subtitles with English only output, or create separate source-language and English subtitle files with Original + English.
- Updated subtitle engine and media processing for better stability across Windows, Linux, and macOS.
- Improved display quality and smoother language switching for Chinese, Japanese, Korean, Thai, and Hindi.
- Clearer CUDA setup and repair flow with background runtime checks.

### v1.1.1 — Stability improvements for subtitle creation

**Date:** June 1, 2026

Voice2Sub 1.1.1 improves subtitle creation reliability, especially on macOS Apple Silicon, and handles long file names, Vietnamese accents, and special characters more smoothly.

- Improved subtitle creation reliability on macOS Apple Silicon.
- Better handling for long file names, Vietnamese accents, and special characters in file paths.
- More reliable checks and recovery for the local processing components used to create subtitles.

### v1.1.0 — Batch subtitle creation and clearer progress tracking

**Date:** May 30, 2026

Voice2Sub 1.1.0 lets you create subtitles for multiple files at once, follow progress more easily, and enjoy more reliable file handling and updates across Windows, macOS, and Linux.

- Create subtitles for multiple audio or video files in one run with the new batch workflow.
- Follow progress more easily with a new processing drawer and clearer status log.
- Improved file selection, drag-and-drop, internal processing reliability, and update reliability on Windows, macOS, and Linux.

### v1.0.5 — Linux support and smoother performance

**Date:** May 20, 2026  

Voice2Sub 1.0.5 adds Linux availability and optimizes overall performance and stability for a smoother, more reliable user experience.

- Voice2Sub is now available for Linux.
- Optimized overall performance and stability for a smoother, more reliable user experience.

### v1.0.4 — Improved license management and safer updates

**Date:** May 18, 2026

Voice2Sub 1.0.4 improves license management reliability and the overall activation experience, while making updates more reliable, safer, and more stable on Windows and macOS.

- Improved license management reliability and overall activation experience.
- Improved update reliability, safety, and stability on Windows and macOS.

### v1.0.3 — Runtime compatibility checks, clearer diagnostics and safer updates

**Date:** May 16, 2026

Voice2Sub 1.0.3 improves Windows runtime compatibility, adds clearer diagnostics for subtitle generation errors, and makes update paths safer for older app versions.

- Windows: Voice2Sub checks for a supported Microsoft Visual C++ Runtime and guides users to install the latest Microsoft runtime when their system is outdated.
- Audio processing and subtitle generation errors now include detailed native process logs, exit codes, and clearer messages.
- Update compatibility is improved for users moving from older app versions.

### v1.0.2 — In-app CUDA setup, clearer download speed and free-duration limit

**Date:** May 13, 2026

Voice2Sub 1.0.2 updates how CUDA is enabled on Windows, improves download progress feedback, and adds a clear duration limit for the free version.

- Windows: CUDA acceleration is managed inside the Windows app. The app detects compatible NVIDIA GPUs and lets users download required CUDA libraries from Settings.
- Download speed is now shown for app updates, CUDA libraries, and AI model downloads.

### v1.0.1 — Audio Quality Enhancement speed and stop/cancel stability

**Date:** May 4, 2026

Voice2Sub 1.0.1 matches the app update notes: faster Audio Quality Enhancement processing and more stable stop/cancel behavior during audio processing.

- Optimized processing speed when using the "Audio Quality Enhancement" option.
- Improved stability when stopping or canceling audio processing.

### v1.0.0 — Initial public release

**Date:** March 20, 2025

The first public release introduced the desktop workflow for turning speech in video or audio into AI subtitles, transcripts and editable text.

- Windows x64 and macOS Apple Silicon builds.
- Windows app later supports optional CUDA acceleration managed inside the app.
- Local speech recognition for offline transcription work.
- 99 recognition languages and support for common media formats.
- Subtitle and plain-text output for creator, learning and documentation workflows.

See the full changelog: [CHANGELOG.md](CHANGELOG.md)

## Supported platforms

- Windows x64
- macOS Apple Silicon
- Linux x64

## Useful links

- Official website: https://voice2sub.pro.vn/
- Download: https://voice2sub.pro.vn/download
- What's new: https://voice2sub.pro.vn/whats-new
- Support: [SUPPORT.md](SUPPORT.md)
- Security policy: [SECURITY.md](SECURITY.md)

## Notes

This repository is used as the public GitHub home for Voice2Sub product information, release notes, support links and issue tracking. The main application source code may remain private.

## Keywords

AI subtitle generator, subtitle generator, speech to text, transcription, audio transcription, video transcription, Whisper transcription, local AI transcription, offline transcription, SRT generator, VTT generator, Windows subtitle app, macOS subtitle app, Linux subtitle app, CUDA transcription, Metal transcription, creator subtitle workflow.
