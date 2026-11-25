# 24cubes

An interactive 3D viewer for Martin Gardner's cube-touching puzzle: how many equal unit cubes can touch the faces of a central cube?

The famous construction by Robert S. Holmes reaches 24 (face distribution 7 + 7 + 6 + 2 + 1 + 1). This repository contains a schematic 3D reconstruction built from the published 2D face patterns, plus the source figures.

> Note: exact non-overlapping 3D coordinates for that specific construction are not published in the accessible sources. The viewer therefore keeps the six face-groups separated so that no cubes intersect; the slider controls that separation.

## Files

- `index.html` — self-contained interactive 3D viewer (drag to orbit, scroll to zoom).
- `boxes.json` — box centers and orientation axes used by the viewer.
- `face-patterns.html` — diagram of the face-by-face construction and the source figures.
- `preview.png` — static render.
- `fig1.png`, `sydKA.png`, `mNN1X.png` — figures from the Puzzling Stack Exchange answer (CC BY-SA 3.0).

## License

MIT — see [LICENSE](LICENSE).
