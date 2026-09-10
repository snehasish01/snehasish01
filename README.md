<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg?v=3">
    <source media="(prefers-color-scheme: light)" srcset="assets/header-light.svg?v=3">
    <img width="860" alt="Snehasish Satpathy. Decision modeling and AI reliability. Drift diffusion sample paths accumulate between two decision boundaries toward a decision point." src="assets/header-light.svg?v=3">
  </picture>
</p>

<p align="center">
  Data scientist by profession. Independently, I research decision modeling, evaluate autonomous LLM agents, and build human AI interaction systems.
</p>

<p align="center">
  BS Statistics and Data Science with a Computer Science minor, University of Arizona
</p>

<p align="center">
  <a href="https://decamint.ai/"><img alt="Decamint, the hiring and assessment platform I cofounded" src="https://img.shields.io/badge/Decamint-6D28D9?style=for-the-badge&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/snehasish-satpathy/"><img alt="Snehasish Satpathy on LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logoColor=white"></a>
  <a href="https://sphur.substack.com/"><img alt="Briefly Aware, my Substack on cognitive science and AI" src="https://img.shields.io/badge/Briefly%20Aware-FF6719?style=for-the-badge&logo=substack&logoColor=white"></a>
  <a href="https://osf.io/5symn"><img alt="My preprints and data on OSF" src="https://img.shields.io/badge/OSF%20preprints-159957?style=for-the-badge&logo=osf&logoColor=white"></a>
  <a href="https://orcid.org/0009-0009-4799-2020"><img alt="My ORCID researcher record" src="https://img.shields.io/badge/ORCID-A6CE39?style=for-the-badge&logo=orcid&logoColor=white"></a>
</p>

<p align="center">
  <img width="860" alt="Section divider marking a new section" src="assets/rule.svg?v=3">
</p>

## Now

- Data scientist at John Deere since July 2023.
- Cofounder of Decamint, an AI native hiring and assessment platform.
- Research in progress: moving Anticipatory Cognitive Dissonance from preprint to an instrumented study, and Project Bathtub from a failure mode taxonomy toward measured hazard rates.

<p align="center">
  <img width="860" alt="Section divider marking a new section" src="assets/rule.svg?v=3">
</p>

## Research

My work asks one question in two settings: how do reasoners, whether human or artificial, judge their own competence, and how often are those judgments wrong. Two commitments follow from taking that seriously.

Model the failure. Before I trust an LLM agent, a benchmark, or a decision procedure, I want its failure mode taxonomy, its hazard rate across the length of a run, and a measured number in place of an impression. Reliability engineering has spent decades formalizing this for aerospace and manufacturing, and most of the apparatus carries over to autonomous software.

Simulate before you trust. A statistical claim is worth making only after the procedure behind it has been run against a known ground truth often enough to show it meets its guarantees. A confidence interval that misses its stated coverage is wrong, whatever the derivation behind it.

<p align="center">
  <img width="860" alt="Section divider marking a new section" src="assets/rule.svg?v=3">
</p>

## Selected work

| Work | What it is | Venue and link |
| --- | --- | --- |
| Project Bathtub, Phase 0 | Failure mode taxonomy for autonomous LLM coding agents. 80 modes across 10 categories, ranked by Risk Priority Number. | [Zenodo, 2026](https://doi.org/10.5281/zenodo.21607993) |
| sinistra | Reproducible high throughput drift diffusion simulation and parameter recovery, with an application to the hand laterality judgement task. | [Zenodo, 2026](https://doi.org/10.5281/zenodo.22693595) |
| Anticipatory Cognitive Dissonance | Preprint. Fires a dissonance inducing prompt while a biased decision is forming rather than after it is committed. | [OSF](https://osf.io/5symn) |
| Project ASTRA | WebXR study that operationalizes Anticipatory Cognitive Dissonance in a VR decision task. | [OSF](https://osf.io/a79qp/overview) |
| Decamint | AI native hiring and assessment platform. Cofounder. | [decamint.ai](https://decamint.ai/) |
| Briefly Aware | Essays on cognitive science, AI, and self knowledge. | [Substack](https://sphur.substack.com/) |

<p align="center">
  <img width="860" alt="Section divider marking a new section" src="assets/rule.svg?v=3">
</p>

## What I work on

### AI reliability and evaluation

Reliability engineering applied to autonomous LLM systems: failure mode taxonomies, criticality ranking by Risk Priority Number, and hazard modeling over a long agent run. Alongside it, the statistics to evaluate model behavior without overclaiming, from bootstrap intervals to sequential testing. The connecting idea is calibration. A system that cannot quantify its own uncertainty is asserting, not measuring.

Repositories: [bathtub-fmea](https://github.com/snehasish01/bathtub-fmea), [eval-power](https://github.com/snehasish01/eval-power), [weibull-bench](https://github.com/snehasish01/weibull-bench), [claude-hooks-toolkit](https://github.com/snehasish01/claude-hooks-toolkit)

### Cognitive and decision modeling

Computational accounts of how people decide under uncertainty: drift diffusion models of the speed accuracy tradeoff, behavioral instrumentation of real choices, and interventions that act in real time. The current thread, Anticipatory Cognitive Dissonance, argues that a biased decision is easiest to redirect while it is still forming.

Repositories: [sinistra](https://github.com/snehasish01/sinistra), [project-astra](https://github.com/snehasish01/project-astra)

### Applied AI and product

Decamint, where I am a cofounder, is an AI native hiring and assessment platform built around structured evaluation of model output. The same interest in making machine behavior observable enough to study runs through the interaction prototypes and the telemetry harnesses.

Link: [decamint.ai](https://decamint.ai/)

### Research and writing

I publish preprints and datasets openly, on OSF and Zenodo. Briefly Aware is my Substack on cognitive science, AI, and self knowledge, written for readers outside the field.

Link: [Briefly Aware](https://sphur.substack.com/)

<p align="center">
  <img width="860" alt="Section divider marking a new section" src="assets/rule.svg?v=3">
</p>

## Toolkit

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/toolkit-dark.svg?v=3">
    <source media="(prefers-color-scheme: light)" srcset="assets/toolkit-light.svg?v=3">
    <img width="860" alt="Toolkit by area. Languages: Python, Rust, SQL, JavaScript. Statistical computing: NumPy, SciPy, pandas, statsmodels, PyMC. ML and systems: PyTorch, scikit-learn, Pydantic, PyO3, Three.js, WebXR. Research infrastructure: Git, pytest, Parquet, LaTeX, Quarto." src="assets/toolkit-light.svg?v=3">
  </picture>
</p>

What I reach for first: Python with NumPy and SciPy for analysis, Rust behind PyO3 when a simulation has to be fast, PyMC when the model is Bayesian, pytest and Parquet to keep results reproducible.

<p align="center">
  <img width="860" alt="Section divider marking a new section" src="assets/rule.svg?v=3">
</p>

## Contact

- **Email:** snehasish.satpathy01@gmail.com
- **LinkedIn:** [linkedin.com/in/snehasish-satpathy](https://www.linkedin.com/in/snehasish-satpathy/)
- **Substack:** [Briefly Aware](https://sphur.substack.com/)
- **Decamint:** [decamint.ai](https://decamint.ai/)
- **ORCID:** [0009-0009-4799-2020](https://orcid.org/0009-0009-4799-2020)
- **Preprints and data:** [OSF](https://osf.io/5symn)
