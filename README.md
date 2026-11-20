# Living Earth Lab · UNIGE enviroSPACE

[![Living Earth](https://livingearthhub.org/assets/img/logos/living-earth-logo.svg)](https://livingearthhub.org)

Code, notebooks, and documentation developed by the **Living Earth Lab** (University of Geneva, enviroSPACE) as a contribution to the [**Living Earth**](https://livingearthhub.org) framework.

> **Living Earth** provides capacity to capture consistent and scalable information on the states and dynamics of past and present landscapes, to inform planning for the future.

🌐 [Living Earth Hub](https://livingearthhub.org) · 🏛️ [Research group page](https://www.unige.ch/envirospace/livingearth) · 📚 [Knowledge Hub](https://livingearthhub.org/knowledge-hub/)

---

## Table of contents

- [About](#about)
- [Scope of this repository](#scope-of-this-repository)
- [Repository structure](#repository-structure)
- [Getting started](#getting-started)
- [Contributing](#contributing)
- [Related projects](#related-projects)
- [Citation](#citation)
- [License](#license)
- [Acknowledgements](#acknowledgements)
- [Contact](#contact)

---

## About

The Living Earth Lab is a research hub dedicated to advancing Earth Observation (EO) data science and Big Earth Data analytics through the Digital Earth framework. Our mission is to contribute to the development and implementation of the Living Earth system by integrating multi-source geospatial data to better understand and model dynamic planetary processes.

Our research covers:

- The science of land change and land degradation
- Impacts of climate change on vegetation and ecosystems
- Sustainability challenges and the environmental effects of urbanization
- Evolution of Earth's geography in deep time and its influence on climate

Living Earth is organised around a digital infrastructure (based on the Open Data Cube) that takes Earth Observation to users through a workflow of:

1. Earth Observation data
2. Environmental descriptors
3. Classification of land cover and habitats
4. Evidence-based change
5. Future landscapes
6. Exploration and delivery

It is currently applied in **Switzerland**, **Wales**, and **Australia**.

## Scope of this repository

This repository is the central place for all Living Earth developments coming from our research group. It is intended to hold, for example:

- Analysis workflows and Jupyter notebooks (land cover, change, degradation, ecosystem condition and accounting, etc.)
- Reusable Python modules and utilities
- Configuration, style files, and example/demo data
- Documentation and tutorials
- Material linked to project deliverables and teaching

> 🔧 *Edit this section to reflect what actually lives in the repo.*

## Repository structure

```text
.
├── notebooks/        # Jupyter notebooks (numbered workflows)
├── src/              # Reusable Python package / modules
├── data/             # Small example or demo data only (no large files)
├── docs/             # Documentation and tutorials
├── styles/           # Map styles and export helpers (e.g. QML)
├── environment.yml   # Reproducible environment
├── CONTRIBUTING.md
├── LICENSE
└── README.md
```

> 🔧 *Adjust to match the real layout.*

## Getting started

### Prerequisites

- Python 3.10+
- A [Google Earth Engine](https://earthengine.google.com/) account (for GEE-based notebooks)
- Conda or mamba (recommended)

### Installation

```bash
git clone https://github.com/<ORG>/<REPO>.git
cd <REPO>

# Create and activate the environment
conda env create -f environment.yml
conda activate livingearth

# Authenticate with Google Earth Engine (first use only)
earthengine authenticate
```

### Running the notebooks

```bash
jupyter lab
```

Where available, notebooks provide a `DEMO_MODE` that runs on small synthetic data, so you can test the workflow without GEE access or large downloads. Configuration parameters are grouped in a single `CONFIG` cell at the top of each notebook.

## Contributing

Contributions from the group and from external collaborators are welcome.

1. **Open an issue** to discuss a bug, a feature, or a new workflow.
2. **Fork** the repository and create a branch (`feature/short-description`).
3. **Make your changes**, keeping to the conventions below.
4. **Open a pull request** describing what changed and why.

**Conventions**

- Notebooks: clear numbered sections, parameters in one top-level config cell, outputs cleared before committing.
- Python code: documented functions, consistent formatting (e.g. `black`, `ruff`).
- Do not commit large datasets, credentials, or API keys.
- Cite data sources and methods in notebooks and docs.

See [CONTRIBUTING.md](CONTRIBUTING.md) for details.

## Related projects

- [Living Earth Hub](https://livingearthhub.org): the Living Earth framework and Knowledge Hub
- [Living Earth Lab](https://www.unige.ch/envirospace/livingearth): our research group at UNIGE
- Projects of the group that feed into this work include Horizon Europe **LandShift**, **MONALISA**, **NEMESIS**, and **Nostradamus**, as well as SNSF **DT4LC**, SNSF **Base-Top Earth**, the **Swiss Data Cube**, and **Living Switzerland**.

## Citation

If you use this repository in your work, please cite it:

```bibtex
@software{livingearth_unige,
  author    = {{Living Earth Lab, University of Geneva}},
  title     = {<REPO NAME>},
  year      = {2026},
  publisher = {GitHub},
  url       = {https://github.com/<ORG>/<REPO>}
}
```

Please also see the [publications of the team](https://www.unige.ch/envirospace/livingearth) and the [Living Earth publications page](https://livingearthhub.org/publications/).

## License

Released under the **<LICENSE NAME>** license. See [LICENSE](LICENSE) for details.

## Acknowledgements

This work is carried out within the Living Earth Lab at the University of Geneva and benefits from the support of the funding programmes and collaborators behind the projects listed above, including Horizon Europe and the Swiss National Science Foundation (SNSF).

> 🔧 *Add the specific grant numbers and funding statements required by each project.*

## Contact

**Living Earth Lab, enviroSPACE, University of Geneva**
🌐 https://www.unige.ch/envirospace/livingearth
✉️ `<contact email>`
