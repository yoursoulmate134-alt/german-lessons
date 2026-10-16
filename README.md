# German Lessons — Android starter

An Android learning app prototype with a professional dark interface, Cyra's anime portrait, quiet lesson mode, German text-to-speech, speech recognition practice, and a guided call-style practice screen.

## Important limitations
- This is a prototype with sample phrases, not a complete A1–C2 course.
- The call screen uses Android speech recognition, local text-to-speech, and scripted beginner replies. It is **not an unrestricted AI chatbot or real telephone call** and does not require a paid AI API.
- Speech recognition depends on a compatible speech service and internet/device support. Core reading lessons and phrase playback are available without a paid subscription.
- Microphone permission is requested when first needed.
- Not yet compiled or device-tested in this environment. Build through GitHub Actions before installing.

## Build APK with GitHub Actions
1. Create a public repository named `german-lessons`.
2. Upload the contents of this folder (the files inside `GermanLessons`, not the outer folder as a single archive).
3. Open **Actions** and run **Build German Lessons Android APK**.
4. Download the `german-lessons-debug-apk` artifact and extract `app-debug.apk`.

The APK is a debug build for testing. Play Store publishing requires a properly signed release bundle and additional setup.
