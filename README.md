# Hello! Welcome to my GitHub profile! 👋

- 🚀 **Full-Stack Developer & Geospatial Engineer** — Building scalable systems at the intersection of AI, GeoTech, and Web Development
- 🏛️ **Research Leader** at [LambdaGeo](https://github.com/LambdaGeo) — Open-source geospatial tools and semantic data integration
- 💼 **Associate Professor** at [UFMA](https://www.ufma.br/) — Ph.D. in Applied Computing from [INPE](https://www.gov.br/inpe/pt-br)

---

## 🚀 Current Focus

### 🌍 DisSModel — Discrete Spatial Modeling Ecosystem

My main research and development focus is **DisSModel**, a modular Python framework for spatially explicit dynamic modeling — designed as a modern, Pythonic alternative to [TerraME](http://www.terrame.org/).

#### [dissmodel](https://github.com/LambdaGeo/dissmodel) — Core library

- **Dual-substrate architecture** — vector (`GeoDataFrame`) for GIS integration, raster (`NumPy`) for high-performance simulation (~4,500× faster at 10k cells)
- **Discrete-event engine** powered by [Salabim](https://www.salabim.org/)
- **Supports** Cellular Automata, System Dynamics, and hybrid spatial models
- **Visualization** — `Map` and `RasterMap` components with headless, Jupyter, Colab, and Streamlit support

| | |
|---|---|
| 📚 Documentation | [lambdageo.github.io/dissmodel](https://lambdageo.github.io/dissmodel/) |
| 📦 PyPI | [pypi.org/project/dissmodel](https://pypi.org/project/dissmodel/) |
| 📖 Book *(work in progress)* | [lambdageo.github.io/geospatial-modeling-python](https://lambdageo.github.io/geospatial-modeling-python/) |

#### [dissmodel-platform](https://github.com/LambdaGeo/dissmodel-platform) — Execution platform

Scalable environment for running DisSModel simulations — from local development to on-premise and cloud clusters.

- **JupyterLab** for interactive development
- **FastAPI** gateway for job submission
- **Distributed workers** with Redis queue (scalable via `docker compose up --scale worker=N`)
- **MinIO** S3-compatible storage for datasets and results
- Runs locally, on-premise (INPE, universities), or on public cloud (AWS, GCP, Azure)

#### Domain plugins

Built on top of `dissmodel`, each plugin adds domain-specific components:

| Plugin | Description | Status |
|--------|-------------|--------|
| **[dissluc](https://github.com/LambdaGeo/dissluc)** | Land-Use Change — CLUE-like allocation and potential regression | active |
| **[coastal-dynamics](https://github.com/LambdaGeo/coastal-dynamics)** | Flood propagation and mangrove migration — Maranhão coast | active |

#### Validation highlights

- `coastal-dynamics` raster vs vector: **100% match** on land use and soil, **19× speedup** at 50k cells
- `dissluc` Lab1 (csAC): validated against TerraME/LuccME reference output

---

