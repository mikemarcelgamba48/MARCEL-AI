# MARCEL AI — Local-first prototype

This is a starter web app for Android. It offers a local UI, browser-local notes and chat history, camera motion detection (frame comparison), and swipe navigation.

## Run
Deploy the folder to GitHub Pages (HTTPS) or another HTTPS host. Camera permission generally requires HTTPS or localhost. Add to home screen from the browser menu.

## Current limits
- Chat is a simple offline demo responder, not a full language model.
- Camera motion comparison runs in-browser while Vision is open; no video is uploaded by this code.
- Swipe/touch navigation is supported. Hand gesture recognition (MediaPipe model) is not yet integrated.
- Browser-local storage can be cleared by browser settings and is not encrypted.
- Service-worker caching is a basic shell cache; it does not guarantee every feature works offline until first visit.

## Next stage
Integrate a downloadable local language model and MediaPipe hand-gesture model, with explicit camera activation and privacy controls.