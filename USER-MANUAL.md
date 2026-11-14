# SceneCraft AI Studio — User Manual
**Version 1.0.0 | Beginner guide**

## 1. What SceneCraft does
SceneCraft helps you plan a film or video project. You can write a script, split it into scenes, arrange a scene sequence, import local media, record narration, create subtitles and download project backups. The app shell can be cached for offline access after the site has been opened online.

This version is an offline-first foundation. It is not yet a full professional editor and does not include built-in AI generation or cloud accounts.

## 2. First launch
1. Publish the project using GitHub Pages (see README).
2. Open the published site while connected to the internet.
3. Wait for the page to finish loading. This allows the app files to be cached.
4. If your browser offers **Install app** or **Add to Home screen**, use it.
5. Reopen SceneCraft from the installed shortcut. The app shell can then open offline, subject to browser storage and cache rules.

## 3. Create a project
1. Open Dashboard.
2. Select **New Project**.
3. Enter a project name.
4. Choose landscape 16:9, portrait 9:16 or square 1:1.
5. Select **Create project**.

Your project is saved in this browser on this device. Clearing browser data may remove it. Download backups regularly.

## 4. Write a script
1. Open **Script & Story**.
2. Select the project.
3. Enter the title, genre and story idea.
4. Write your screenplay in the large script box.
5. Select **Save script**.

## 5. Create a storyboard
1. Open **Storyboard** and select your project.
2. Select **Add scene**.
3. Edit the scene title, description and duration in seconds.
4. Use ↑ and ↓ to reorder scenes.
5. Use × to remove a scene.

Scene descriptions should explain the shot, location, action, mood and camera view.

## 6. Preview your scene order
1. Open **Timeline Editor**.
2. Select your project.
3. Select **Preview**.
4. Scene cards appear in order for the duration assigned to each scene.

This is a scene-sequence preview, not a multi-track video editor.

## 7. Import media
1. Open **Media Library**.
2. Select **Add media**.
3. Choose image, video or audio files.
4. Imported files are stored in browser-managed local data for the project.

This release limits each imported file to 35 MB to reduce storage problems. Device/browser storage limits still apply. If you need to preserve media, keep the original files in a separate folder as well.

## 8. Record narration
1. Open **Voice & Audio**.
2. Select your project.
3. Press **Start recording**.
4. Allow microphone access when asked.
5. Press **Stop** when finished.
6. Play the saved recording using the audio player.

Microphone recording normally requires a secure website (HTTPS) or localhost. Keep recordings short while testing, because long recordings can use substantial storage.

## 9. Add captions and export subtitles
1. Open **Captions**.
2. Select **Add caption**.
3. Enter start and end times in `HH:MM:SS,mmm` format.
4. Enter the subtitle text.
5. Select **Export .SRT**.

Example time: `00:00:12,500` means 12.5 seconds.

## 10. Export a project backup
1. Open **Export & Backup**.
2. Select the project.
3. Select **Download project backup**.
4. Keep the downloaded `.scenecraft.json` file somewhere safe.

To restore it, go to Dashboard → **Import project** and choose the backup file. A backup may be large if it contains imported media or recordings.

## 11. Render a simple storyboard video
1. Open **Export & Backup**.
2. Select the project under Storyboard video.
3. Choose landscape, portrait or square.
4. Select **Render storyboard video**.
5. Keep the page open until the download starts.

The current renderer creates scene cards from text and descriptions and downloads a WebM file. It does not combine imported video clips, music tracks, transitions or effects into a finished movie. Browser support and device performance vary.

## 12. Offline operation
- Open the published site online at least once so the app shell can be cached.
- The project data is local to the browser and device.
- Editing, writing, scene arrangement and local project backups work without an AI connection.
- Do not clear site data if you have projects that are not backed up.
- Browser storage can be removed by device cleanup tools or browser settings. Keep regular backups.

## 13. AI and cloud services
AI image/video generation, automatic script generation, speech-to-text and cloud backup are not active in this version. They require separate providers or local models. Free plans can have quotas, change their terms, or stop being free. No paid API, payment method, cloud account or billing service is configured here.

Never publish private API keys in a public GitHub repository or put secret keys in browser JavaScript.

## 14. Troubleshooting
**The site will not open offline:** Open it online once, refresh, and check that the browser allows site data. Service workers require HTTPS or localhost.

**Microphone does not work:** Use the HTTPS GitHub Pages address, allow microphone permission and check that another app is not using the microphone.

**Media will not import:** Try a smaller file (35 MB maximum per file in this version) and check available device storage.

**Project disappeared:** Check whether you opened the same browser and same device. Import a previously downloaded backup if available.

**Video render is unsupported:** Try a current Chrome or Edge browser. Some mobile browsers do not support canvas recording or the selected WebM codec.

**Storage full:** Download project backups, keep original media outside the browser, then remove unnecessary project media or projects.

## 15. Safe working habits
- Export backups after important work sessions.
- Keep original media files in a separate folder.
- Do not use browser private/incognito mode for long-term projects.
- Do not delete site data unless backups are available.
- Test microphone and video export with short samples before a long session.
