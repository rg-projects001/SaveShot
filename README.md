# SaveShot

Screenshot-to-action Android MVP.

## Current pipeline
- Detects recent screenshots
- OCR with ML Kit
- Classifies screenshots as task, recipe, shopping, or reference
- Surfaces an actionable notification
- Builds a debug APK through GitHub Actions

CI is intentionally kept independent of third-party Android SDK setup actions and uses the Android SDK preinstalled on GitHub-hosted runners.
