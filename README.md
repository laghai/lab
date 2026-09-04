# lab.dmitrydimov.com

Static publishing hub. One path per track.

- `/` landing
- `/board/` — Cloud Olympics scoreboard
- `/olympics/` — the catalog: one hero artifact per event
- `/venus/` — a captured 3-D Gaussian splat

Pages here are generated from the `cloud-platform` repo and published by
`bin/catalog-publish`. Every figure shown is gated: it must appear in that repo's
measured record, and every hero names the execution that produced it.

Large media (video, imagery, point clouds) is served from object storage, not committed here.
