# Navi Movement Videos for Realistic MuJoCo Simulation

This repository is a coworker-facing motion reference for reproducing Navi as realistically as possible in MuJoCo.

## Watch the videos

Open **[the public playable video library](https://wesleyfan2015.github.io/Navi-Videos/)** to watch all 43 actual MP4 videos with their corresponding Agentech SDK commands.

GitHub's normal file view may say that an MP4 is too large to show. That is only a GitHub preview limitation; use the playable library above, or click **View raw** for an individual file.

## Contents

- `videos/movements/`: 5 translational movement videos
- `videos/actions/`: 31 Action Command videos
- `videos/athletics/`: 7 Athletic Command videos
- `videos/*/SHA256SUMS.txt`: SHA-256 integrity manifests

All videos are browser-compatible H.264 MP4 files at 1600×1200, 30 fps, `yuv420p`, with fast-start metadata. Each file was fully decoded without errors, visually checked for robot motion, copied to Windows, and hash-matched against the Mac output.

The newest recording was one continuous 20-command batch, executed in this exact order:

1. `Agentech.clap_hand()`
2. `Agentech.sniff_right()`
3. `Agentech.front_stretch()`
4. `Agentech.cute()`
5. `Agentech.ask_for_play()`
6. `Agentech.enjoy_touch()`
7. `Agentech.sniff_left()`
8. `Agentech.sniff_ahead()`
9. `Agentech.full_body_stretch()`
10. `Agentech.push_up(count=3)`
11. `Agentech.look_around()`
12. `Agentech.think()`
13. `Agentech.observe()`
14. `Agentech.yawn()`
15. `Agentech.wave_hand()`
16. `Agentech.bow()`
17. `Agentech.wag_rear()`
18. `Agentech.bark()`
19. `Agentech.nod_head()`
20. `Agentech.shake_head()`

These motion-only cuts replace the older canonical videos for Action items 6–11 and 16–29. The filenames, numbering, and total library count remain stable.

## Recommended MuJoCo use

Use the videos to estimate phase timing, footfall order, base translation, body-height changes, roll/pitch/yaw excursions, landing compliance, recovery timing, and expressive pose targets. Canonical filenames stay stable when a cleaner recording replaces an older clip; recording-batch execution order is documented above and on the playback page.
