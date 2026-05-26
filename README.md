Examples of technical features
# 🪐 Viz-Atlas Astronomy & Data Ingestion Research

Welcome! This repository documents my raw research, API connectors mapping, data queries, and protocol definitions that power the **Viz-Atlas** 3D platform.

The main target of my research is to systematically map data from trusted scientific space agency databases and translate them into custom JSON structures suitable for local 3D rendering (WebGL) on the frontend, and decentralized on-chain storage via smart contracts.

## 📁 Repository Map

### 1. `/queries`
This folder contains the actual structured queries used to pull data directly from scientific astronomy servers:
* **`nasa_exoplanets.adql`**: Table queries targeting confirmed systems, filtering missing astronomical attributes.
* **`simbad_tap.adql`**: Astronomical Data Query Language targeting brightest stars coordinates to translate 2D sky projections into 3D cartesian coordinates $(X, Y, Z)$ inside the engine.

### 2. `/specs`
Details of JSON schemas that represent physical units formatted for the decentralized smart-contract registry:
* Conversion of Parallax (milliarcseconds) to Light Years ($D = 1000 / \pi$).
* Stellar temperature map coordinates matched with real custom star colors.

---
## 🎓 Application for University Admissions
This work represents my independent scientific and research efforts in software systems engineering. I will be proud to discuss ADQL queries, celestial metadata structures, and the physical algorithms behind 3D simulations during technical university admissions and academic interviews.
