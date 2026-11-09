# My AI Studio — Android Starter v1

A free, offline-first Android starter project for a personal viral-video workflow.

## Included in v1
- Home dashboard and workflow overview
- Research desk with category selector and fact-check checklist
- Short (30–60 sec) and long (10–15 min) script-outline templates
- Draft approval queue; nothing is uploaded automatically
- No API keys, paid subscriptions, or account connections required

## Important limitations
This is a starter app, not yet a fully AI-powered publisher. Trend discovery, live source verification, AI writing, voice generation, video rendering, thumbnail generation, persistent cloud storage, and YouTube OAuth/upload are not connected in this version. The script template is a scaffold, not factual research. Verify all claims and rights to media before publishing.

## Build
1. Install Android Studio (free) on a computer.
2. Open this folder as an existing Gradle project.
3. Use JDK 17 and Android Gradle Plugin 8.7.3.
4. Let Gradle sync, then run on an Android phone (Android 7.0/API 24 or newer) with USB debugging enabled.

## Next milestones
- v1.1: save drafts locally with Room; export script and production brief.
- v1.2: connect an AI text provider using a secure backend (never embed secret API keys in the APK).
- v1.3: connect source search and citation capture.
- v1.4: add voice, image/video assets, captions and FFmpeg rendering.
- v1.5: connect YouTube OAuth and upload as private/unlisted; require explicit in-app approval before publishing.

## Privacy and security
Do not put API keys or YouTube client secrets directly in the Android app. Use OAuth for YouTube and a small backend for provider keys. Request only permissions needed for the selected feature.
