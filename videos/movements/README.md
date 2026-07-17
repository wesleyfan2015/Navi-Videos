# Navi movement videos

Clean movement-only reference clips for SDK users and simulation work.

| Order | Movement | Video | SDK velocity mapping |
|---:|---|---|---|
| 1 | Backward | [01_backward.mp4](01_backward.mp4) | `linear < 0`, `lateral = 0`, `angular = 0` |
| 2 | Lateral left | [02_lateral_left.mp4](02_lateral_left.mp4) | `linear = 0`, `lateral > 0`, `angular = 0` |
| 3 | Lateral right | [03_lateral_right.mp4](03_lateral_right.mp4) | `linear = 0`, `lateral < 0`, `angular = 0` |
| 4 | Diagonal left-backward | [04_diagonal_left_backward.mp4](04_diagonal_left_backward.mp4) | `linear < 0`, `lateral > 0`, `angular = 0` |
| 5 | Diagonal right-forward | [05_diagonal_right_forward.mp4](05_diagonal_right_forward.mp4) | `linear > 0`, `lateral < 0`, `angular = 0` |

Calibrate the camera, robot, and world coordinate frames before relying on the lateral signs. All files are browser-compatible 1600 × 1200, 30 fps H.264 MP4 videos with fast-start metadata.

File hashes are recorded in [SHA256SUMS.txt](SHA256SUMS.txt).
