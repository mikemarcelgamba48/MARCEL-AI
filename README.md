# MARCEL Android starter

This is an Android Studio/Gradle project that packages the existing local-first MARCEL web prototype inside an Android WebView.

## Build an APK using GitHub Actions
1. Upload the entire contents of this folder to the root of a GitHub repository (not just the ZIP).
2. Open the repository's Actions tab.
3. Select **Build MARCEL APK** and run it, or push the files to `main`.
4. When the workflow succeeds, open its run and download the `MARCEL-debug-apk` artifact.
5. Extract the artifact ZIP; install `app-debug.apk` on your Android phone.

## Honest current scope
- This is an Android app shell around the existing local prototype.
- The included chat is a limited demo responder, not a real language model.
- Camera motion detection is browser-frame comparison while the camera screen is active.
- Hand-pose recognition and a local LLM are NOT integrated yet.
- The app needs explicit Android camera permission for camera use.
- This starter has not been compiled or device-tested here. GitHub Actions builds the APK.

## Device considerations
A 4 GB RAM phone is constrained. Start with a very small quantized model (if later integrated) and test memory use; 6 GB free storage does not guarantee sufficient RAM for every model.
