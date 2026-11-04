# QGMP

Quantum-conditioned cryptic pocket intelligence: an interactive demonstration of apo protein structures, quantum relational messages, geometric features, and residue-level pocket predictions.

## Website

https://magic-fortune.github.io/QGMP/

## Run locally

```sh
python3 -m http.server 8000
```

Open http://localhost:8000/ with WebGL enabled.

## Deployment

GitHub Pages serves the `main` branch from the repository root. The page uses relative URLs, with its 3Dmol library and molecular data included locally.

## Data provenance

`qc_demo2_data.json` contains the existing D038-GVP checkpoint prediction bundle and evaluation presentation data. The molecular showcase is `2X47 A → 6LH4 D`. Benchmark values are copied from the project's evaluation records; this website does not run a new evaluation.
