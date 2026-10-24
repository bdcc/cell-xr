# CellXR

Reach in and take the cell apart.

A hand-tracked 3D cell viewer that runs in the browser, with or without a camera.
The camera feed (if used) needs **https or localhost**; hand tracking runs on your device — nothing is uploaded or stored.

## Live

https://bdcc.github.io/cell-xr/

## Run locally

```sh
python3 -m http.server 8000
```

Then open <http://localhost:8000/>

## Open a specific model

Append `?model=` to point at any glTF/GLB:

```
cell-xr.html?model=models/animal-cell.web.glb
```

## Controls

| Gesture set | Action |
|---|---|
| 1 Grab | Pick up and move parts |
| 2 Spin | Rotate the cell |
| 3 Navigate | Pan / zoom |
| 4 Pointer | Select parts |

| Key | Action |
|---|---|
| B | Explode |
| U | Undo |
| R | Reset |
| C | Collapse panel |
| Tab | Cycle selection |
| Esc | Dismiss |
| Enter / arrows | Navigate tutorial |

## Credits

See [CREDITS.md](CREDITS.md).
