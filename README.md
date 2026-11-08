# Sérgio Souza Costa

**Associate Professor of Computer Engineering** @ [UFMA](https://www.ufma.br) · **Geospatial Data Engineer** · **Open Science Advocate**  
🎓 PhD in Applied Computing, [INPE](https://www.inpe.br) (National Institute for Space Research), Brazil  
📍 São Luís, Brazil · 🌍 Open to international research collaborations & postdoctoral opportunities (targeting 2028)

> I lead the [LambdaGeo](https://lambdageo.ufma.br) research group. My work is on reproducible spatial simulation, land-change modelling, and the open data and software infrastructure behind it.

### 🔗 Links

<p align="left">
  <a href="https://lambdageo.ufma.br"><img src="https://img.shields.io/badge/LambdaGeo-research_group-1565C0?style=flat" alt="LambdaGeo" /></a>
  <a href="https://lambdageo.ufma.br/people/sergio-costa/"><img src="https://img.shields.io/badge/Profile-lambdageo.ufma.br-2E7D32?style=flat" alt="Profile" /></a>
  <a href="https://scholar.google.com/citations?user=ggu2II0AAAAJ&hl=en"><img src="https://img.shields.io/badge/Google_Scholar-Profile-4285F4?style=flat&logo=google-scholar&logoColor=white" alt="Google Scholar" /></a>
  <a href="https://orcid.org/0000-0002-0232-4549"><img src="https://img.shields.io/badge/ORCID-0000--0002--0232--4549-A6CE39?style=flat&logo=orcid&logoColor=white" alt="ORCID" /></a>
  <a href="http://lattes.cnpq.br/2073311645132958"><img src="https://img.shields.io/badge/Lattes-CV-263238?style=flat" alt="Lattes" /></a>
  <a href="https://www.linkedin.com/in/profsergiocosta/"><img src="https://img.shields.io/badge/LinkedIn-profsergiocosta-1565C0?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
</p>

---

## 📦 Open-source software

### Python packages on PyPI

**Spatial simulation and land-change modelling**

| Package | What it does | Stats |
|---|---|---|
| [**dissmodel**](https://pypi.org/project/dissmodel/) | Core framework for discrete spatial simulation, with built-in experiment records. `pip install dissmodel` | <a href="https://pypi.org/project/dissmodel/"><img src="https://img.shields.io/pypi/v/dissmodel?label=version&color=blue" alt="version" /></a> <img src="https://img.shields.io/pypi/dm/dissmodel?label=downloads&color=green" alt="downloads" /> |
| [**disscube**](https://pypi.org/project/disscube/) | Declarative spatial data cubes: a TOML file turns open sources (MapBiomas, PRODES, BDC, OSM, DEM) into gridded model inputs, with provenance. `pip install disscube` | <a href="https://pypi.org/project/disscube/"><img src="https://img.shields.io/pypi/v/disscube?label=version&color=blue" alt="version" /></a> <img src="https://img.shields.io/pypi/dm/disscube?label=downloads&color=green" alt="downloads" /> |
| [**disslucc**](https://pypi.org/project/disslucc/) | Land-use/cover change components (demand, potential, allocation), verified against LuccME. `pip install disslucc` | <a href="https://pypi.org/project/disslucc/"><img src="https://img.shields.io/pypi/v/disslucc?label=version&color=blue" alt="version" /></a> <img src="https://img.shields.io/pypi/dm/disslucc?label=downloads&color=green" alt="downloads" /> |

**Field data and semantic web**

| Package | What it does | Stats |
|---|---|---|
| [**fielddash**](https://pypi.org/project/fielddash/) | Schema-driven Streamlit dashboards for Epicollect5 field surveys: filters, charts and maps come from the form schema, and a new survey needs only a YAML file ([docs](https://lambdageo.github.io/fielddash/)). `pip install fielddash` | <a href="https://pypi.org/project/fielddash/"><img src="https://img.shields.io/pypi/v/fielddash?label=version&color=blue" alt="version" /></a> <img src="https://img.shields.io/pypi/dm/fielddash?label=downloads&color=green" alt="downloads" /> |
| [**rdfmapper**](https://pypi.org/project/rdfmapper/) | Declarative Object–RDF mapper for Python. `pip install rdfmapper` | <a href="https://pypi.org/project/rdfmapper/"><img src="https://img.shields.io/pypi/v/rdfmapper?label=version&color=blue" alt="version" /></a> <img src="https://img.shields.io/pypi/dm/rdfmapper?label=downloads&color=green" alt="downloads" /> |

Model collections and the agent-based extension ([dissmodel-ca](https://github.com/DisSModel/dissmodel-ca), [dissmodel-sysdyn](https://github.com/DisSModel/dissmodel-sysdyn), [dissmodel-abm](https://github.com/DisSModel/dissmodel-abm)) are installed from tagged GitHub releases.

### QGIS plugins

| Plugin | What it does | Get it |
|---|---|---|
| [**QGISSPARQL**](https://plugins.qgis.org/plugins/qgisparql/) | Import SPARQL query results as layers and export layers as RDF | QGIS Plugin Manager |
| [**DisSCube for QGIS**](https://github.com/LambdaGeo/disscube-qgis) | Draw the study area on the map, build the grid and DisSCube TOML files, run and load the result | [Release ZIP](https://github.com/LambdaGeo/disscube-qgis/releases/tag/v0.1.5) · [DOI](https://doi.org/10.5281/zenodo.24033974) |

### Reproducibility and verification

[terrame-docker](https://github.com/LambdaGeo/terrame-docker) · [luccme-goldens](https://github.com/LambdaGeo/luccme-goldens) · [terrame-goldens](https://github.com/LambdaGeo/terrame-goldens) · [disscube-benchmark](https://github.com/LambdaGeo/disscube-benchmark) · [disslucc-benchmark](https://github.com/LambdaGeo/disslucc-benchmark) · [open-lucc-workflow](https://github.com/LambdaGeo/open-lucc-workflow) · [disscube-grids](https://github.com/LambdaGeo/disscube-grids)

---

## 🏛️ Research & Educational Ecosystems

My research and teaching code lives in three GitHub organizations, not on this personal profile.

| | Organization | Focus & Flagship Projects |
|---|---|---|
| 🌍 | **[LambdaGeo](https://github.com/LambdaGeo)** · [Site](https://lambdageo.ufma.br) | Research group: spatial computing, geotechnologies and Linked Data; reference outputs, benchmarks and study cases for DisSModel. Examples: [QGISSPARQL](https://plugins.qgis.org/plugins/qgisparql/) (QGIS plugin), [rdfmapper](https://pypi.org/project/rdfmapper/) (Object-RDF mapper), [fielddash](https://pypi.org/project/fielddash/) (field survey dashboards). |
| 🧩 | **[DisSModel](https://github.com/DisSModel)** · [Site](https://dissmodel.github.io) | Python ecosystem for discrete spatial simulation and land-change modelling, an independent alternative to INPE's TerraME/LuccME (which remain the reference). [PyPI](https://pypi.org/project/dissmodel/) · Under review at JOSS. |
| 🎓 | **[LambdaGeo Edu](https://github.com/lambdageo-edu)** · [Site](https://lambdageo-edu.github.io) | Open educational materials (in Portuguese): Compilers (Nand2Tetris), Functional Programming, Data Structures, Geoprocessing and Remote Sensing. |

### 📚 Books

- *Geospatial Modeling with Python*: [LambdaGeo/geospatial-modeling-python](https://github.com/LambdaGeo/geospatial-modeling-python)
- *Introdução ao Geoprocessamento e Sensoriamento Remoto* (pt-BR): [lambdageo-edu](https://lambdageo-edu.github.io/book-geoprocessamento-e-sensoriamento-remoto/)

---

## 📊 Impact at a glance

<p align="left">
  <a href="https://github.com/profsergiocosta"><img src="https://img.shields.io/github/followers/profsergiocosta?label=followers&style=flat" alt="followers" /></a>
  <a href="https://github.com/DisSModel/dissmodel"><img src="https://img.shields.io/github/stars/DisSModel/dissmodel?label=dissmodel%20stars&style=flat" alt="dissmodel stars" /></a>
  <a href="https://github.com/DisSModel/disscube"><img src="https://img.shields.io/github/stars/DisSModel/disscube?label=disscube%20stars&style=flat" alt="disscube stars" /></a>
  <a href="https://github.com/DisSModel/disslucc"><img src="https://img.shields.io/github/stars/DisSModel/disslucc?label=disslucc%20stars&style=flat" alt="disslucc stars" /></a>
  <a href="https://github.com/LambdaGeo/fielddash"><img src="https://img.shields.io/github/stars/LambdaGeo/fielddash?label=fielddash%20stars&style=flat" alt="fielddash stars" /></a>
</p>

<p align="left">
  <a href="https://pepy.tech/project/dissmodel"><img src="https://img.shields.io/pepy/dt/dissmodel?label=dissmodel%20downloads&color=green" alt="dissmodel total downloads" /></a>
  <a href="https://pepy.tech/project/disscube"><img src="https://img.shields.io/pepy/dt/disscube?label=disscube%20downloads&color=green" alt="disscube total downloads" /></a>
  <a href="https://pepy.tech/project/disslucc"><img src="https://img.shields.io/pepy/dt/disslucc?label=disslucc%20downloads&color=green" alt="disslucc total downloads" /></a>
  <a href="https://pepy.tech/project/fielddash"><img src="https://img.shields.io/pepy/dt/fielddash?label=fielddash%20downloads&color=green" alt="fielddash total downloads" /></a>
</p>

---

## 💻 Technical Stack

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Haskell-5D4F85?style=flat&logo=haskell&logoColor=white" alt="Haskell" />
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white" alt="Go" />
  <img src="https://img.shields.io/badge/Java-007396?style=flat&logo=java&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/Clojure-5881D8?style=flat&logo=clojure&logoColor=white" alt="Clojure" />
  <img src="https://img.shields.io/badge/RDF/SPARQL-FF0000?style=flat&logo=w3c&logoColor=white" alt="Semantic Web" />
  <img src="https://img.shields.io/badge/GeoPandas-317943?style=flat&logo=python&logoColor=white" alt="GeoPandas" />
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white" alt="Streamlit" />
  <img src="https://img.shields.io/badge/QGIS-589632?style=flat&logo=qgis&logoColor=white" alt="QGIS" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white" alt="Docker" />
</p>

---

## 📌 About this profile

This profile (`profsergiocosta`) holds personal experiments, small utilities and side projects. For research code, spatial modelling software and courseware, see the organizations above.

---

<sub>Associate Professor · UFMA · São Luís, Brazil · Building open and reproducible geospatial simulations.</sub>
