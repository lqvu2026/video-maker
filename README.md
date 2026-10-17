# Video Maker

A single-page web app that turns a background image and an audio file into a video exactly as long as the audio. Everything runs in the browser; nothing is uploaded.

## Features
- Background image + audio file, video length = audio length
- Fade in / fade out (from and to black, with the sound), fade length 0.5 to 5 seconds
- Aspect ratios: 16:9 (default), 9:16, 1:1, 4:3, 3:4, 4:5, 21:9
- Resolutions: 480p, 720p, 1080p (default), 1440p, 4K
- Image fit: fill (crop), fit with blurred background, fit with black bars
- File size: Small / Balanced / High quality (estimate shown before you create)
- Save or Share the finished video

## Files
- `index.html` (the whole app)
- `video-maker-icon.png` (180x180 Home Screen icon, make your own and keep this file name)
- `README.md`

## Publish on GitHub Pages
1. Create a repo (for example `video-maker`) and commit `index.html`, `video-maker-icon.png` and `README.md`.
2. Settings > Pages > deploy from the main branch.
3. After 1-2 minutes open `https://<your-user>.github.io/video-maker/`.
4. On iPhone: Safari > Share > Add to Home Screen.

## Notes
- The video is recorded in real time (a 4-minute song takes about 4 minutes). Keep the page open and the screen on.
- Safari and recent Chrome save MP4 (H.264 + AAC). Other browsers may save WebM.
- Output is limited to 3840 pixels on the long side.
