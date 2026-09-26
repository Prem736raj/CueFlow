# CueFlow

CueFlow is a lightweight Android teleprompter with local script management, rehearsal and recording tools, a draggable floating overlay, optional speech-driven prompting, and a temporary local-network remote.

## Highlights

- Create, edit, organize, and search scripts locally.
- Run a floating teleprompter above other Android apps.
- Rehearse with timing and pace feedback.
- Record with CameraX when camera and microphone permissions are granted.
- Import user-requested web pages and link-accessible Google Docs.
- Use optional speech recognition and a session-paired Wi-Fi remote.

CueFlow does not require a CueFlow account, and the current release is designed without advertising or analytics SDKs.

## Build

Use the committed Gradle wrapper:

```bash
./gradlew testDebugUnitTest
./gradlew lintDebug
./gradlew assembleDebug
```

On Windows, use `gradlew.bat`.

## Product and privacy documentation

- [Privacy Policy](PRIVACY_POLICY.md)
- [Google Play Store Listing](STORE_LISTING.md)
- [Play Release Checklist](PLAY_RELEASE_CHECKLIST.md)

The core script editor and prompting experience are local-first. Features that inherently need connectivity, such as online imports, are user initiated.
