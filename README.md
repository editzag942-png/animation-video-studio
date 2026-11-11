# Animation Video Studio

A free, Android-friendly starter workspace for preparing animated reels.

## Current website features
- Script and character-description input
- Scene breakdown and reusable animation prompt
- Local audio preview
- Lightweight stylized 2D canvas preview
- Browser recording/export (MP4 only if the browser supports it; otherwise WebM)
- JSON project export and basic offline caching

## Important limitation
This GitHub Pages app is **not** an AI video generator. Its preview uses locally drawn 2D characters and simple deterministic movement. It does not generate arbitrary AI characters, production-quality 3D animation, automatic lip-sync, or guaranteed MP4 conversion.

## Claude workflow
The `CLAUDE.md` file contains the intended one-command production instructions. Add that file to a Claude Project's instructions/knowledge and connect the actual video-generation/rendering tools available in that Claude environment. Then provide the script and audio and say **"Make the reel."**

The instruction file coordinates tools; it does not itself provide video-generation capability. A connected renderer/video tool is still required to produce the finished animated video.

## Free-only rule
No paid APIs, paid credits, subscriptions, or billing are part of this project. If a free tool has limits, report them honestly.

## Deploy
Enable GitHub Pages for the `main` branch, root folder. Open the Pages URL in Android Chrome. Use Chrome's menu → Add to Home screen if you want an app-like shortcut.
