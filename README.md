# Sérgio Souza Costa

**Associate Professor of Computer Engineering** @ [UFMA](https://www.ufma.br) · **Geospatial Data Engineer** · **Open Science Advocate**  
🎓 PhD in Applied Computing, [INPE](https://www.inpe.br) (National Institute for Space Research), Brazil  
📍 São Luís, Brazil · 🌍 Open to international research collaborations & postdoctoral opportunities (targeting 2028)

> I lead the [LambdaGeo](https://lambdageo.ufma.br) research group. My work is on reproducible spatial simulation, land-change modelling, and the open data and software infrastructure behind it.

### 🔗 Links
[

![LambdaGeo](https://img.shields.io/badge/LambdaGeo-research_group-1565C0?style=flat)

](https://lambdageo.ufma.br)
[

![Profile](https://img.shields.io/badge/Profile-lambdageo.ufma.br-2E7D32?style=flat)

](https://lambdageo.ufma.br/people/sergio-costa/)
[

![Google Scholar](https://img.shields.io/badge/Google_Scholar-Profile-4285F4?style=flat&logo=google-scholar&logoColor=white)

](https://scholar.google.com/citations?user=ggu2II0AAAAJ&hl=en)
[

![ORCID](https://img.shields.io/badge/ORCID-0000--0002--0232--4549-A6CE39?style=flat&logo=orcid&logoColor=white)

](https://orcid.org/0000-0002-0232-4549)
[

![Lattes](https://img.shields.io/badge/Lattes-CV-263238?style=flat)

](http://lattes.cnpq.br/2073311645132958)
[

![LinkedIn](https://img.shields.io/badge/LinkedIn-profsergiocosta-1565C0?style=flat&logo=linkedin&logoColor=white)

](https://www.linkedin.com/in/profsergiocosta/)

---

## 📦 Open-source software

### Python packages on PyPI

**Spatial simulation and land-change modelling**

| Package | What it does | Version | Downloads | Install |
|---|---|---|---|---|
| [**dissmodel**](https://pypi.org/project/dissmodel/) | Core framework for discrete spatial simulation, with built-in experiment records | [

![PyPI](https://img.shields.io/pypi/v/dissmodel.svg?label=&color=blue)

](https://pypi.org/project/dissmodel/) | 

![downloads](https://img.shields.io/pypi/dm/dissmodel.svg?label=&color=green)

 | `pip install dissmodel` |
| [**disscube**](https://pypi.org/project/disscube/) | Declarative spatial data cubes: a TOML file turns open sources (MapBiomas, PRODES, BDC, OSM, DEM) into gridded model inputs, with provenance | [

![PyPI](https://img.shields.io/pypi/v/disscube.svg?label=&color=blue)

](https://pypi.org/project/disscube/) | 

![downloads](https://img.shields.io/pypi/dm/disscube.svg?label=&color=green)

 | `pip install disscube` |
| [**disslucc**](https://pypi.org/project/disslucc/) | Land-use/cover change components (demand, potential, allocation), verified against LuccME | [

![PyPI](https://img.shields.io/pypi/v/disslucc.svg?label=&color=blue)

](https://pypi.org/project/disslucc/) | 

![downloads](https://img.shields.io/pypi/dm/disslucc.svg?label=&color=green)

 | `pip install disslucc` |

**Field data and semantic web**

| Package | What it does | Version | Downloads | Install |
|---|---|---|---|---|
| [**fielddash**](https://pypi.org/project/fielddash/) | Schema-driven Streamlit dashboards for Epicollect5 field surveys: filters, charts and maps come from the form schema, and a new survey needs only a YAML file ([docs](https://lambdageo.github.io/fielddash/)) | [

![PyPI](https://img.shields.io/pypi/v/fielddash.svg?label=&color=blue)

](https://pypi.org/project/fielddash/) | 

![downloads](https://img.shields.io/pypi/dm/fielddash.svg?label=&color=green)

 | `pip install fielddash` |
| [**rdfmapper**](https://pypi.org/project/rdfmapper/) | Declarative Object–RDF mapper for Python | [

![PyPI](https://img.shields.io/pypi/v/rdfmapper.svg?label=&color=blue)

](https://pypi.org/project/rdfmapper/) | 

![downloads](https://img.shields.io/pypi/dm/rdfmapper.svg?label=&color=green)

 | `pip install rdfmapper` |

Model collections and the agent-based extension ([dissmodel-ca](https://github.com/DisSModel/dissmodel-ca), [dissmodel-sysdyn](https://github.com/DisSModel/dissmodel-sysdyn), [dissmodel-abm](https://github.com/DisSModel/dissmodel-abm)) are installed from tagged GitHub releases.

### QGIS plugins

| Plugin | What it does | Get it |
|---|---|---|
| [**QGISSPARQL**](https://plugins.qgis.org/plugins/qgisparql/) | Import SPARQL query results as layers and export layers as RDF | QGIS Plugin Manager |
| [**DisSCube for QGIS**](https://github.com/LambdaGeo/disscube-qgis) | Draw the study area on the map, build the grid and DisSCube TOML files, run and load the result | [Release ZIP](https://github.com/LambdaGeo/disscube-qgis/releases/tag/v0.1.5) · [DOI](https://doi.org/10.5281/zenodo.24033974) |

### Reproducibility and verification

[`terrame-docker`](https://github.com/LambdaGeo/terrame-docker) · [`luccme-goldens`](https://github.com/LambdaGeo/luccme-goldens) · [`terrame-goldens`](https://github.com/LambdaGeo/terrame-goldens) · [`disscube-benchmark`](https://github.com/LambdaGeo/disscube-benchmark) · [`disslucc-benchmark`](https://github.com/LambdaGeo/disslucc-benchmark) · [`open-lucc-workflow`](https://github.com/LambdaGeo/open-lucc-workflow) · [`disscube-grids`](https://github.com/LambdaGeo/disscube-grids)

---

## 🏛️ Research & Educational Ecosystems

My research and teaching code lives in three GitHub organizations, not on this personal profile.

| | Organization | Focus & Flagship Projects |
|---|---|---|
| 🌍 | **[LambdaGeo](https://github.com/LambdaGeo)** · [Site](https://lambdageo.ufma.br) | Research group: spatial computing, geotechnologies and Linked Data; reference outputs, benchmarks and study cases for DisSModel.<br>*(e.g., [QGISSPARQL](https://plugins.qgis.org/plugins/qgisparql/) – QGIS plugin; [rdfmapper](https://pypi.org/project/rdfmapper/) – Object-RDF mapper; [fielddash](https://pypi.org/project/fielddash/) – field survey dashboards)* |
| 🧩 | **[DisSModel](https://github.com/DisSModel)** · [Site](https://dissmodel.github.io) | Python ecosystem for discrete spatial simulation and land-change modelling, an independent alternative to INPE's TerraME/LuccME (which remain the reference).<br>*(📦 [PyPI](https://pypi.org/project/dissmodel/) · 📝 Under review at JOSS)* |
| 🎓 | **[LambdaGeo Edu](https://github.com/lambdageo-edu)** · [Site](https://lambdageo-edu.github.io) | Open educational materials (in Portuguese): Compilers (Nand2Tetris), Functional Programming, Data Structures, Geoprocessing and Remote Sensing. |

### 📚 Books

- *Geospatial Modeling with Python* · [LambdaGeo/geospatial-modeling-python](https://github.com/LambdaGeo/geospatial-modeling-python)
- *Introdução ao Geoprocessamento e Sensoriamento Remoto* (pt-BR) · [lambdageo-edu](https://lambdageo-edu.github.io/book-geoprocessamento-e-sensoriamento-remoto/)

---

## 📊 GitHub stats

<p align="left">
  <img height="170" alt="GitHub stats" src="https://github-readme-stats.vercel.app/api?username=profsergiocosta&show_icons=true&count_private=true&include_all_commits=true&hide_border=true" />
  <img height="170" alt="Top languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=profsergiocosta&layout=compact&langs_count=8&hide_border=true" />
</p>

<p align="left">
  <img alt="Contribution streak" src="https://streak-stats.demolab.com/?user=profsergiocosta&hide_border=true" />
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
