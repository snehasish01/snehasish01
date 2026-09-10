<!-- ────────────────────────────────────────────────────────────────── -->
<!--  snehasish01 · profile README                                       -->
<!-- ────────────────────────────────────────────────────────────────── -->

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:070d1a,45:143a6b,100:2f81f7&height=210&section=header&text=Snehasish%20Satpathy&fontSize=44&fontColor=ffffff&fontAlignY=36&animation=fadeIn&desc=cognitive%20science%20%C2%B7%20applied%20AI%20%C2%B7%20the%20science%20of%20knowing%20what%20you%20know&descSize=15&descAlignY=56" alt="Snehasish Satpathy" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com/?font=JetBrains+Mono&weight=600&size=21&pause=900&color=4C9AFF&center=true&vCenter=true&width=820&height=42&lines=Data+scientist+%C2%B7+cognitive+science+%C3%97+applied+AI;Reliability+%26+evaluation+for+autonomous+LLM+systems;Computational+models+of+decision-making+under+uncertainty;Building+AI-native+hiring+assessment+at+Decamint" alt="what I work on" />
</p>

<p align="center">
  <a href="https://decamint.ai/"><img src="https://img.shields.io/badge/Decamint-AI--native%20hiring-6D28D9?style=for-the-badge&logoColor=white" alt="Decamint" /></a>
  <a href="https://osf.io/5symn"><img src="https://img.shields.io/badge/OSF-ACD%20research-159957?style=for-the-badge&logo=osf&logoColor=white" alt="OSF preprint" /></a>
  <a href="https://doi.org/10.5281/zenodo.21607993"><img src="https://img.shields.io/badge/Zenodo-published%20DOI-1682D4?style=for-the-badge&logo=zenodo&logoColor=white" alt="Zenodo DOI" /></a>
  <a href="https://sphur.substack.com/"><img src="https://img.shields.io/badge/Substack-Briefly%20Aware-FF6719?style=for-the-badge&logo=substack&logoColor=white" alt="Briefly Aware" /></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Data%20Scientist-John%20Deere-367C2B?style=flat-square&labelColor=2b3137" alt="Data Scientist @ John Deere" />
  <img src="https://img.shields.io/badge/AI%20reliability%20%26%20evaluation-B45309?style=flat-square" alt="AI reliability & evaluation" />
  <img src="https://img.shields.io/badge/cognitive%20%26%20decision%20modeling-6D28D9?style=flat-square" alt="cognitive & decision modeling" />
  <img src="https://img.shields.io/badge/human%E2%80%93AI%20interaction-0D9488?style=flat-square" alt="human-AI interaction" />
</p>

---

## About

I'm a data scientist working where cognitive science meets applied AI. One question
runs through everything I do, in two forms: **how do people — and now autonomous
agents — form beliefs, judge their own competence, and decide under uncertainty?**

Two commitments shape how I approach it:

- **Systems fail, so model the failure.** Before trusting an LLM agent, a benchmark,
  or a decision process, I want its failure-mode taxonomy, its hazard rate over time,
  and a measured number — not an impression. Reliability engineering has spent eighty
  years formalizing this for aerospace and automotive; most of it transfers.
- **Simulate before you trust.** A statistical claim earns its keep only when the
  procedure that produced it has been run thousands of times against a known ground
  truth and hit its nominal guarantees. A confidence interval that misses its coverage
  is wrong no matter how elegant the derivation.

<br>

## What I work on

### 🛡️ AI reliability & evaluation

Bringing reliability-engineering discipline — FMEA, criticality ranking, survival and
hazard modeling — to **autonomous LLM coding agents**, a class of system that is
increasingly trusted and barely characterized. Alongside it, the statistical machinery
to evaluate model behavior honestly: bootstrap confidence intervals, paired significance
testing, minimum-detectable-effect and power analysis, sequential testing with error
control. The throughline is **calibration** — a system or a benchmark that cannot
quantify its own uncertainty is asserting, not measuring.

<sub>Project Bathtub · <a href="https://doi.org/10.5281/zenodo.21607993">published FMEA taxonomy (DOI)</a> · agent-evaluation statistics · developer tooling for agent observability</sub>

### 🧠 Cognitive & decision modeling

Computational accounts of how people decide under uncertainty: **drift-diffusion models**
of the speed–accuracy trade-off, behavioral instrumentation of real choices, and
real-time debiasing. My current research thread — **Anticipatory Cognitive Dissonance** —
argues that the right moment to interrupt a biased decision is *while it is still forming*,
before commitment, and tests that claim with instrumented decision environments.

<sub><a href="https://osf.io/5symn">ACD preprint (OSF)</a> · reaction-time modeling in Rust + Python · WebXR decision-bias prototype</sub>

### 🚀 Applied AI & product

Turning the research into things people use. **Decamint** is an AI-native
hiring-assessment platform — assessment design that measures capability rather than
keyword overlap. I also build human–AI interaction prototypes and instrumentation that
makes agent behavior observable enough to study.

<sub><a href="https://decamint.ai/">Decamint</a> · human–AI interaction · agent telemetry harnesses</sub>

### ✍️ Research & writing

I publish preprints and data openly, and write **[Briefly Aware](https://sphur.substack.com/)** —
a Substack on cognitive science, AI, and self-knowledge for a general audience.

<br>

## Selected work

| | | |
|---|---|---|
| **Project Bathtub — Phase 0 (FMEA)** | Reliability-engineering failure-mode taxonomy for AI coding agents; 80 modes across 10 categories, ranked by Risk Priority Number | [Zenodo · 10.5281/zenodo.21607993](https://doi.org/10.5281/zenodo.21607993) |
| **Anticipatory Cognitive Dissonance** | Preprint: interrupting decision bias as it forms, in anticipatory AI tutors | [OSF · osf.io/5symn](https://osf.io/5symn) |
| **Project ASTRA** | WebXR study operationalizing ACD — detects forming decision bias from behavioral signal and interrupts with an LLM-generated question before commitment | [OSF · osf.io/a79qp](https://osf.io/a79qp/overview) |
| **sinistra** | Preprint: reproducible high-throughput drift-diffusion simulation and parameter recovery, applied to the hand laterality judgement task | [Zenodo · 10.5281/zenodo.22693595](https://doi.org/10.5281/zenodo.22693595) |
| **Decamint** | AI-native hiring-assessment platform | [decamint.ai](https://decamint.ai/) |
| **Briefly Aware** | Essays on cognitive science, AI, and self-knowledge | [sphur.substack.com](https://sphur.substack.com/) |

<sub>Open-source projects — drift-diffusion modeling, Weibull estimator benchmarking, LLM-evaluation statistics, agent-observability tooling — are on the <a href="https://github.com/snehasish01?tab=repositories">repositories tab</a>.</sub>

<br>

## Toolkit

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" alt="Rust" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white" alt="SQL" />
  <img src="https://img.shields.io/badge/LaTeX-008080?style=flat-square&logo=latex&logoColor=white" alt="LaTeX" />
</p>
<p>
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=4DABCF" alt="NumPy" />
  <img src="https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white" alt="SciPy" />
  <img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="pandas" />
  <img src="https://img.shields.io/badge/statsmodels-3B5FA8?style=flat-square&logoColor=white" alt="statsmodels" />
  <img src="https://img.shields.io/badge/PyMC-2A2D7C?style=flat-square&logo=python&logoColor=FFD43B" alt="PyMC" />
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="scikit-learn" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch" />
  <img src="https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white" alt="Pydantic" />
  <img src="https://img.shields.io/badge/PyO3-000000?style=flat-square&logo=rust&logoColor=DEA584" alt="PyO3" />
  <img src="https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=threedotjs&logoColor=white" alt="Three.js" />
  <img src="https://img.shields.io/badge/WebXR-EF6C4D?style=flat-square&logo=webgl&logoColor=white" alt="WebXR" />
  <img src="https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white" alt="pytest" />
</p>

<br>

<p align="center">
  <sub>
    <a href="https://decamint.ai/">Decamint</a> ·
    <a href="https://osf.io/5symn">ACD preprint</a> ·
    <a href="https://doi.org/10.5281/zenodo.21607993">Project Bathtub</a> ·
    <a href="https://sphur.substack.com/">Briefly Aware</a>
  </sub>
</p>
