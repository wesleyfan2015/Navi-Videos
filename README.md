# Navi Movement Videos for Realistic MuJoCo Simulation

This repository is a coworker-facing motion reference for reproducing Navi as realistically as possible in MuJoCo.

## Watch the videos

Open **[the public playable video library](https://wesleyfan2015.github.io/Navi-Videos/)** to watch all 39 actual MP4 videos with their corresponding Agentech SDK commands.

GitHub's normal file view may say that an MP4 is too large to show. That is only a GitHub preview limitation; use the playable library above, or click **View raw** for an individual file.

## Contents

- `videos/movements/`: 5 translational movement videos
- `videos/actions/`: 27 Action Command videos
- `videos/athletics/`: 7 Athletic Command videos
- `videos/*/SHA256SUMS.txt`: SHA-256 integrity manifests

All videos are browser-compatible H.264 MP4 files at 1600×1200, 30 fps, `yuv420p`, with fast-start metadata. Each file was fully decoded without errors, visually checked for robot motion, copied to Windows, and hash-matched against the Mac output.

## Recommended MuJoCo use

Use the videos to estimate phase timing, footfall order, base translation, body-height changes, roll/pitch/yaw excursions, landing compliance, recovery timing, and expressive pose targets. The numbering preserves the physical execution order inside each group.
