# SceneCraft AI Studio

An offline-first, browser-based creative workspace for planning and assembling scene-based video projects.

## Included in this release
- Project dashboard with local project creation and JSON import/export.
- Script and story editor.
- Storyboard with editable scenes, duration and reorder controls.
- Scene-sequence preview.
- Local media library for images, video and audio (browser storage limits apply).
- Microphone narration recorder.
- Caption editor and SRT subtitle export.
- Basic scene-card WebM renderer using browser MediaRecorder.
- PWA manifest and service worker for app-shell offline access.
- Beginner learning centre and user manual.

## Important scope and limitations
This is a functional starter release, not a finished professional non-linear editor. It does not yet provide frame-accurate multi-track editing of arbitrary source video, advanced transitions, automatic speech recognition, AI image generation, text-to-video generation, cloud sync, user accounts, or native APK/Windows EXE installers.

The scene-card renderer exports a video containing scene titles and descriptions. It does not combine imported video clips into a full edit. Browser support varies. Exported project backups can become large because media data is included.

## Run locally
Open `index.html` in a modern browser. Some features (PWA installation, service worker and microphone recording) require HTTPS or localhost. For the offline app experience, publish to GitHub Pages and open it once while online.

## Publish with GitHub Pages
1. Upload the contents of this folder to the root of your GitHub repository.
2. In GitHub, open **Settings → Pages**.
3. Under Build and deployment, select **Deploy from a branch**.
4. Select branch `main` and folder `/ (root)`, then Save.
5. Wait for the Pages deployment and open the URL shown by GitHub.
6. Open the site once online. Use your browser's install option if available.

## Privacy and costs
No API key, paid service, account, or payment method is included. This release stores project data in the current browser on the current device. It does not upload your work to a cloud server. Do not add secret API keys to public repository files.
