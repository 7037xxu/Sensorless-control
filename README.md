# Sensorless-control project page

This folder contains an experimental GitHub Pages website for full-speed-range sensorless AFPM operation.

## Publish with GitHub Pages

1. Upload everything in this folder to the root of the `Sensorless-control` repository.
2. Open `Settings > Pages` in GitHub.
3. Select `Deploy from a branch`, then choose `main` and `/(root)`.
4. Save and wait for deployment.

The resulting URL will be:

`https://7037xxu.github.io/Sensorless-control/`

## Add the four videos

Put MP4 files in `assets/videos/` using these exact names:

| Experiment | Required filename |
|---|---|
| Test bench inspection | `test-bench.mp4` |
| ±10 r/min operation | `10rpm.mp4` |
| ±1500 r/min operation | `1500rpm.mp4` |
| Sinusoidal position tracking | `sinusoidal-tracking.mp4` |

The page detects these files automatically. Until a file is present, its video card displays a `Video coming soon` placeholder.

Recommended encoding: MP4 container, H.264 video, AAC audio, 1080p or 720p. Keep each file below GitHub's per-file upload limit. For larger files, compress them before uploading or host them externally.
