<!-- ────────────────────────────────────────────────────────────────── -->
<!--  snehasish01 · profile README                                       -->
<!-- ────────────────────────────────────────────────────────────────── -->

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1f3a5f,100:3776AB&height=190&section=header&text=Snehasish%20Satpathy&fontSize=42&fontColor=ffffff&fontAlignY=34&desc=Cognitive%20science%20%C2%B7%20AI%20%C2%B7%20self-knowledge%2C%20applied%20to%20whatever%20I%27m%20building&descSize=15&descAlignY=54" alt="Snehasish Satpathy" />
</p>

<p align="center">
  <a href="https://decamint.ai/"><img src="https://img.shields.io/badge/Decamint-AI--native%20hiring-3776AB?style=for-the-badge&logoColor=white" alt="Decamint" /></a>
  <a href="https://osf.io/5symn"><img src="https://img.shields.io/badge/OSF-ACD%20preprint-1f6feb?style=for-the-badge&logo=osf&logoColor=white" alt="OSF preprint" /></a>
  <a href="https://doi.org/10.5281/zenodo.21607993"><img src="https://img.shields.io/badge/Zenodo-Project%20Bathtub-024dad?style=for-the-badge&logo=zenodo&logoColor=white" alt="Zenodo DOI" /></a>
  <a href="https://sphur.substack.com/"><img src="https://img.shields.io/badge/Briefly%20Aware-Substack-FF6719?style=for-the-badge&logo=substack&logoColor=white" alt="Briefly Aware" /></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Data%20Scientist-John%20Deere-367C2B?style=flat-square" alt="Data Scientist @ John Deere" />
  <img src="https://img.shields.io/badge/focus-reliability%20engineering%20for%20LLM%20agents-555555?style=flat-square" alt="focus" />
  <img src="https://img.shields.io/badge/method-simulate%2C%20don%27t%20assume-555555?style=flat-square" alt="method" />
</p>

---

## About

I work at the intersection of **cognitive science, AI, and self-knowledge** — how people
(and now agents) form beliefs, misjudge their own competence, and decide. That runs through
everything below in two recurring habits:

- **Treat systems as things that fail.** Whether it's an LLM coding agent or a career
  decision in VR, I want the failure-mode taxonomy, the hazard rate, and the number — not a
  vibe.
- **Validate by simulation, not by formula.** A confidence interval that doesn't hit its
  nominal coverage across thousands of synthetic runs is wrong, no matter how good the
  derivation looks.

| | |
|---|---|
| 🏢 **Day job** | Data Scientist @ John Deere |
| 🚀 **Building** | [**Decamint**](https://decamint.ai/) — an AI-native hiring-assessment platform |
| 🔬 **Researching** | [**Anticipatory Cognitive Dissonance**](https://osf.io/5symn) — interrupting decision bias *as it forms*, before commitment lock-in |
| ✍️ **Writing** | [**Briefly Aware**](https://sphur.substack.com/) — a Substack on cognitive science, AI, and self-knowledge |

<br>

## 🛁 Project Bathtub — reliability engineering for AI coding agents

[![DOI](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.21607993-024dad?style=flat-square)](https://doi.org/10.5281/zenodo.21607993)
![Phase 0](https://img.shields.io/badge/Phase%200-published-3fb950?style=flat-square)
![Phase 1](https://img.shields.io/badge/Phase%201-in%20progress-d29922?style=flat-square)

A research program that applies classical **Failure Mode and Effects Analysis (FMEA)** and
**survival analysis** — reliability-engineering disciplines with roots in 1940s aerospace —
to a domain that has no structured hazard prioritization yet: **autonomous LLM coding agents.**

> **Headline finding (Phase 0).** Ranked by Risk Priority Number, *verification /
> self-assessment* and *specification / communication* failures land at or above every
> hallucination-related mode. Hallucinated APIs are real — but a compiler catches them. An
> agent claiming it ran tests it never ran does not get caught, and costs just as much.

<table>
  <tr>
    <td width="210"><a href="https://github.com/snehasish01/bathtub-fmea"><b>bathtub-fmea</b></a><br><sub>Python · TeX · ⭐ 1</sub></td>
    <td>The Phase 0 artifact — an <b>80-item failure-mode taxonomy</b> across 10 categories, each scored on Severity / Occurrence / Detectability and ranked by RPN. Ships the preprint (Zenodo DOI), the full FMEA workbook, and the figures.</td>
    <td width="140"><img src="https://img.shields.io/badge/paper-published-3fb950?style=flat-square" alt="published" /></td>
  </tr>
  <tr>
    <td><a href="https://github.com/snehasish01/eval-power"><b>eval-power</b></a><br><sub>Python · SciPy · statsmodels</sub></td>
    <td>Statistical toolkit for comparing LLM outputs — <b>bootstrap CIs, paired McNemar / bootstrap tests, minimum-detectable-effect sizing, sequential testing with alpha spending</b>. Warns loudly when a reported model difference is within noise. Every method validated by simulating the actual procedure end-to-end.</td>
    <td><img src="https://img.shields.io/badge/oracle-validated-3fb950?style=flat-square" alt="validated" /></td>
  </tr>
  <tr>
    <td><a href="https://github.com/snehasish01/weibull-bench"><b>weibull-bench</b></a><br><sub>Python · PyMC · SciPy</sub></td>
    <td>Simulation study benchmarking <b>four Weibull estimators</b> (MLE, method-of-moments, probability-plot regression, Bayesian) under censoring — real bias / RMSE and credible-interval coverage numbers, not one <code>fit()</code> call. Buttresses the bathtub-curve hazard-rate claims in the paper.</td>
    <td><img src="https://img.shields.io/badge/estimators-verified-3fb950?style=flat-square" alt="verified" /></td>
  </tr>
  <tr>
    <td><a href="https://github.com/snehasish01/fmea-engine"><b>fmea-engine</b></a><br><sub>Python · Pydantic · Typer</sub></td>
    <td>Turns the taxonomy paper into runnable software: a <b>schema for failure-mode taxonomies</b> where RPN is derived code, never an authored field, plus a consistency validator. Ships the published 80-item taxonomy as validated reference data.</td>
    <td><img src="https://img.shields.io/badge/schema%20%2B%20validator-done-d29922?style=flat-square" alt="in progress" /></td>
  </tr>
  <tr>
    <td><a href="https://github.com/snehasish01/claude-hooks-toolkit"><b>claude-hooks-toolkit</b></a><br><sub>Python · Claude Code hooks</sub></td>
    <td>The Phase 1 instrumentation: a reusable <b>Claude Code hook harness</b> — installer CLI, pluggable extractors, JSONL / Parquet sinks — gated by a 50-check end-to-end test that installs into a throwaway project, fires real hook events, and reads schema-valid rows back off disk.</td>
    <td><img src="https://img.shields.io/badge/core%20harness-working-d29922?style=flat-square" alt="in progress" /></td>
  </tr>
</table>

<sub><b>Roadmap:</b> Phase 0 taxonomy + RPN (done) → Phase 1 instrumentation & telemetry (in progress) → Phase 2 hazard modeling: fit <code>h(step)</code> against step-indexed logs, test the error-compounding hypothesis → Phase 3 surface calibrated reliability data back to users.</sub>

<br>

## 🧠 Cognitive science & decision modeling

<table>
  <tr>
    <td width="210"><a href="https://github.com/snehasish01/sinistra"><b>sinistra</b></a><br><sub>Rust core · Python bindings (PyO3)</sub></td>
    <td>
      A <b>drift-diffusion model</b> simulator and parameter-recovery engine — the standard account of fast two-alternative decisions. Recovers parameters two independent ways (closed-form <b>EZ-diffusion</b> and <b>simulation-based Nelder–Mead fitting</b>), hits <b>~1.5M trials/sec</b> and is bit-reproducible per seed. Applied to a real hand-laterality dataset, it localizes the biomechanical-constraints effect to a <b>drift-rate</b> drop, not a boundary shift.
      <br><br>
      <a href="https://pypi.org/project/sinistra/"><img src="https://img.shields.io/pypi/v/sinistra?style=flat-square&logo=pypi&logoColor=white&label=pip%20install%20sinistra&color=3776AB" alt="PyPI" /></a>
      <img src="https://img.shields.io/badge/cargo-sinistra--cli-000000?style=flat-square&logo=rust&logoColor=white" alt="crates.io" />
    </td>
    <td width="140"><img src="https://img.shields.io/badge/published-3fb950?style=flat-square" alt="published" /></td>
  </tr>
  <tr>
    <td><a href="https://github.com/snehasish01/project-astra"><b>project-astra</b></a><br><sub>JavaScript · Three.js · WebXR</sub></td>
    <td>
      A <b>WebXR proof-of-concept</b> for Anticipatory Cognitive Dissonance. Runs in-headset on a Meta Quest 3S, instruments a VR career-decision scenario in real time (head-gaze dwell, reading depth, branch-visit order), classifies the emerging bias pattern, and fires a single <b>LLM-generated question that cites the user's own behavioral trace</b> — <i>before</i> they lock in a choice, not after.
      <br><br>
      <a href="https://osf.io/a79qp/overview"><img src="https://img.shields.io/badge/OSF-project%20page-1f6feb?style=flat-square&logo=osf&logoColor=white" alt="OSF" /></a>
    </td>
    <td><img src="https://img.shields.io/badge/PoC-verified-d29922?style=flat-square" alt="proof of concept" /></td>
  </tr>
</table>

<br>

## 📄 Selected writing & research

| | |
|---|---|
| **Project Bathtub: A Reliability-Engineering Approach to Failure-Mode Taxonomy for AI Coding Agents (Phase 0 — FMEA)** | Zenodo, 2026 · [10.5281/zenodo.21607993](https://doi.org/10.5281/zenodo.21607993) |
| **Cognitive dissonance as a trigger for intervention in anticipatory AI tutors** | OSF preprint · [osf.io/5symn](https://osf.io/5symn) |
| **Briefly Aware** — essays on cognitive science, AI, and self-knowledge | [sphur.substack.com](https://sphur.substack.com/) |

<br>

## 🛠 Stack

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" alt="Rust" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/LaTeX-008080?style=flat-square&logo=latex&logoColor=white" alt="LaTeX" />
</p>
<p>
  <img src="https://img.shields.io/badge/NumPy-555555?style=flat&logo=numpy&logoColor=white" alt="NumPy" />
  <img src="https://img.shields.io/badge/SciPy-555555?style=flat&logo=scipy&logoColor=white" alt="SciPy" />
  <img src="https://img.shields.io/badge/pandas-555555?style=flat&logo=pandas&logoColor=white" alt="pandas" />
  <img src="https://img.shields.io/badge/statsmodels-555555?style=flat&logoColor=white" alt="statsmodels" />
  <img src="https://img.shields.io/badge/PyMC-555555?style=flat&logo=python&logoColor=white" alt="PyMC" />
  <img src="https://img.shields.io/badge/Pydantic-555555?style=flat&logo=pydantic&logoColor=white" alt="Pydantic" />
  <img src="https://img.shields.io/badge/PyO3-555555?style=flat&logo=rust&logoColor=white" alt="PyO3" />
  <img src="https://img.shields.io/badge/Three.js-555555?style=flat&logo=threedotjs&logoColor=white" alt="Three.js" />
  <img src="https://img.shields.io/badge/WebXR-555555?style=flat&logo=webxr&logoColor=white" alt="WebXR" />
  <img src="https://img.shields.io/badge/pytest-555555?style=flat&logo=pytest&logoColor=white" alt="pytest" />
</p>

<br>

## 📊 GitHub

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=snehasish01&theme=transparent" alt="profile summary" />
</p>

<p align="center">
  <img height="180" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=snehasish01&theme=transparent" alt="repos per language" />
  <img height="180" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=snehasish01&theme=transparent" alt="most-committed languages" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=snehasish01&hide_border=true&background=00000000&stroke=80808055&ring=3776AB&fire=3776AB&currStreakLabel=808080&sideLabels=808080&dates=80808099&currStreakNum=808080&sideNums=808080" alt="contribution streak" />
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
