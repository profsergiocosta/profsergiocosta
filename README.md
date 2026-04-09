eu# Hello! Welcome to my GitHub profile! 👋

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

---

### 🧠 [IntegrAI](https://github.com/profsergiocosta)

A platform for healthcare professionals using a microservices architecture with **Django**, **Docker**, **LLM integration**, and AI-driven decision support.

---

## 🌍 LambdaGeo — Open-Source Geospatial Projects

- **[dissmodel](https://github.com/LambdaGeo/dissmodel)** — Discrete spatial modeling framework (Cellular Automata + System Dynamics)
- **[coastal-dynamics](https://github.com/LambdaGeo/coastal-dynamics)** — Coastal flood and mangrove simulation (DisSModel case study)
- **[qgisparql-layer2triple](https://github.com/LambdaGeo/qgisparql-layer2triple)** — Export QGIS vector layers as RDF triples (Turtle format)
- **[qgisparql-triple2layer](https://github.com/LambdaGeo/qgisparql-triple2layer)** — Import linked data from SPARQL endpoints into QGIS
- **[rdfmapper](https://github.com/LambdaGeo/rdfmapper)** — Declarative Object-RDF Mapper for Python
- **[DBCells](https://github.com/LambdaGeo/dbcells)** — Architecture for publishing spatial modeling data as Linked Data

---

## 🎓 Teaching

### 🛠️ [Polyglot-Compilers](https://github.com/profsergiocosta/polyglot-compilers)
Compiler design and formal languages — implementing **Nand2Tetris**, **Lox**, **Eva**, and **C--** across **C++, Go, Python, Clojure,** and **Elixir**.

---

## 🛠 Languages and Tools

**Software Engineering** — C++, Go, Python, Haskell, Clojure, Elixir · Django, Node.js, Spring Boot · Docker, AWS, CI/CD

**Geospatial** — GeoPandas, NumPy, rasterio, libpysal · Google Earth Engine · QGIS (PyQGIS) · PostGIS · RDF / SPARQL (Fuseki)

---

## 📊 GitHub Overview

<p align="center">
  <img height="160em" src="https://github-readme-stats.vercel.app/api?username=profsergiocosta&show_icons=true&theme=dark&include_all_commits=true" />
  <img height="160em" src="https://github-readme-streak-stats.herokuapp.com/?user=profsergiocosta&theme=dark&hide_border=false" />
</p>

---

## 📬 Connect

- 📝 [Notion profile](https://profsergiocosta.notion.site/)
- 🔗 [GitHub Activity](https://github.com/profsergiocosta)

---

<p align="center">
  <a href="https://github.com/profsergiocosta">
    <img src="http://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=profsergiocosta&theme=transparent" />
  </a>
</p>

