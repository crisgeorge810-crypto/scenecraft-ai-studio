# Product roadmap

This roadmap is planning information, not a claim that the features are already implemented.

## Foundation included in v1.0
- Offline-first PWA shell and local project data
- Script, storyboard, scene ordering and duration
- Media import, narration recording and SRT captions
- Scene-card preview and basic WebM rendering
- JSON project backup and restore
- User manual

## Next engineering phases
1. IndexedDB media storage and resilient autosave/recovery.
2. True timeline model with tracks, clip in/out points, snapping and trim.
3. Video decode/encode pipeline with browser capability checks and fallback export.
4. Audio tracks, gain, fades, mixing and waveform display.
5. Transitions, titles, filters and subtitle burn-in.
6. Local speech recognition where supported, with explicit offline model downloads only where licensing and device capacity allow.
7. Optional AI provider adapters with visible provider, quota, privacy and cost controls. No paid provider should ever activate silently.
8. Optional encrypted cloud backup with user-controlled connection and conflict handling.
9. Android packaging and Windows desktop packaging after the web application is stable.
10. A matching tutorial video series recorded against the completed UI.

## Architecture principles
- Local-first project ownership.
- Explicit opt-in for network features.
- No API secrets in client code.
- No surprise billing or automatic paid upgrades.
- Honest capability checks and clear export limitations.
