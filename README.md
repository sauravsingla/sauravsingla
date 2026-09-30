<div align="center">

# Saurav Singla

### Building open-source systems for reliable ML, AI agents, efficient LLM inference & dynamic graphs

`ML Reliability` · `Agentic AI` · `LLM Systems` · `Graph Analytics` · `C++ / Python`

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Saurav%20Singla-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sauravsingla008)
[![Google Scholar](https://img.shields.io/badge/Google%20Scholar-Research-4285F4?logo=googlescholar&logoColor=white)](https://scholar.google.com/citations?user=1rUZyEAAAAAJ&hl=en)
[![Hugging Face](https://img.shields.io/badge/Hugging%20Face-sauravsingla08-FFD21E)](https://huggingface.co/sauravsingla08)
[![ORCID](https://img.shields.io/badge/ORCID-0000--0002--6404--3988-A6CE39?logo=orcid&logoColor=white)](https://orcid.org/0000-0002-6404-3988)

**Open-source projects built around measurable, reproducible evidence ↓**

</div>

---

## ⭐ Featured — [DeciShift](https://github.com/sauravsingla/DeciShift)

### Your model metrics improved. Did its actual decisions change?

DeciShift is an open-source ML behavioral regression testing framework that compares two versions of a decision system, finds record-level action changes, attributes those changes to versioned components, preserves verifiable evidence, and can block a release when declared Decision Contracts are violated.

**Public evaluation example:** model accuracy improved from **90.26% → 91.79%**, yet **30 of 719 final actions changed**; a governed cohort exceeded its declared action-shift limit, so the release contract returned **BLOCK**.

`ML Testing` · `MLOps` · `Model Governance` · `Decision Systems` · `Python`

[![GitHub stars](https://img.shields.io/github/stars/sauravsingla/DeciShift?style=social)](https://github.com/sauravsingla/DeciShift)

[⭐ Explore / Star](https://github.com/sauravsingla/DeciShift) · [PyPI](https://pypi.org/project/decishift/) · [Live Demo](https://huggingface.co/spaces/sauravsingla08/DeciShift) · [Dataset](https://huggingface.co/datasets/sauravsingla08/DeciShift-Decision-Change-Benchmark)

```bash
pip install decishift
decishift demo --rows 1000 --no-save
```

---

## 02 — 🧠 [AgentWeave](https://github.com/sauravsingla/agentweave)

**Route before you reason.**

Pre-inference routing and secure execution for tool-rich LLM and multi-agent systems. AgentWeave reduces the action space shown to a model before inference while keeping authorization, provenance and recovery explicit.

**Project benchmark:** 70.18% fewer tools exposed · 61.70% fewer input tokens · 50.95% lower mean local-model latency

`MCP` · `A2A` · `LangGraph` · `AutoGen` · `Python`

[![GitHub stars](https://img.shields.io/github/stars/sauravsingla/agentweave?style=social)](https://github.com/sauravsingla/agentweave)

[⭐ Explore / Star](https://github.com/sauravsingla/agentweave) · [PyPI](https://pypi.org/project/agentweave-router/) · [Docs](https://sauravsingla.github.io/agentweave/) · [Paper](https://arxiv.org/abs/2608.23078)

---

## 03 — ⚙️ [MemVanta](https://github.com/sauravsingla/MemVanta)

**Run quantized LLMs with less resident memory.**

A memory-first C++20 runtime for quantized GGUF models on CPU, built around mmap-backed model access, paged KV cache, compact kernels and reproducible benchmarking.

**7B benchmark:** 3.80 GiB peak RSS · 47.54% lower peak RSS than the pinned comparison runtime

`C++20` · `GGUF` · `CPU Inference` · `Systems`

[![GitHub stars](https://img.shields.io/github/stars/sauravsingla/MemVanta?style=social)](https://github.com/sauravsingla/MemVanta)

[⭐ Explore / Star](https://github.com/sauravsingla/MemVanta) · [PyPI](https://pypi.org/project/memvanta/) · [Docs](https://sauravsingla.github.io/MemVanta/) · [Benchmark](https://sauravsingla.github.io/MemVanta/benchmark/)

---

## 04 — 🕸️ [VeloGraphX](https://github.com/sauravsingla/VeloGraphX)

**High-performance analytics for continuously evolving graphs.**

A C++20 + Python engine for dynamic graph analytics with adaptive repair vs recomputation across BFS/SSSP, connected components, triangle counting, k-core and PageRank.

**Retained exactness stress result:** 2,000,000 updates · 0 BFS mismatches · 0 triangle mismatches

`C++20` · `Python` · `Dynamic Graphs` · `Graph Analytics` · `PyPI`

[![GitHub stars](https://img.shields.io/github/stars/sauravsingla/VeloGraphX?style=social)](https://github.com/sauravsingla/VeloGraphX)

[⭐ Explore / Star](https://github.com/sauravsingla/VeloGraphX) · [Docs](https://sauravsingla.github.io/VeloGraphX/) · [PyPI](https://pypi.org/project/velographx/)

---

## 05 — 🎯 [ConfigReach](https://github.com/sauravsingla/ConfigReach)

**Codecov for configuration space.**

A deterministic, CPU-only configuration coverage analyzer that shows which environment variables, feature flags, configuration values, branches and important combinations your tests actually exercise.

**Published validation:** 11 pinned repositories · 9 ecosystems · 96,845 configuration inputs · 5,539 with detected test/runtime evidence · 5.72% aggregate observed configuration coverage

`Software Testing` · `Static Analysis` · `Configuration Coverage` · `CI/CD` · `Python`

[![GitHub stars](https://img.shields.io/github/stars/sauravsingla/ConfigReach?style=social)](https://github.com/sauravsingla/ConfigReach)

[⭐ Explore / Star](https://github.com/sauravsingla/ConfigReach) · [Hugging Face Collection](https://huggingface.co/collections/sauravsingla08/configreach-configuration-coverage) · [Space](https://huggingface.co/spaces/sauravsingla08/ConfigReach) · [Dataset](https://huggingface.co/datasets/sauravsingla08/configreach-validation) · [PyPI](https://pypi.org/project/configreach/)

```bash
pip install configreach
configreach scan .
configreach coverage .
```

---

## Open-source approach

I try to make projects useful beyond a demo: **benchmarks, reproducible evidence, tests, releases, documentation and explicit claim boundaries** alongside the code.

If one of these projects solves a problem you care about, **star that project repository** so others can discover it too. Issues, benchmark reproductions, integrations and technical feedback are also welcome.

---

## Research & Publications

[Google Scholar](https://scholar.google.com/citations?user=1rUZyEAAAAAJ&hl=en) · [IEEE Xplore](https://ieeexplore.ieee.org/author/678288976748329) · [ORCID](https://orcid.org/0000-0002-6404-3988) · [DBLP](https://dblp.org/pid/410/2745.html) · [OpenReview](https://openreview.net/profile?id=~Saurav_Singla1) · [ACM DL](https://dl.acm.org/profile/99661729658)

**Book:** *Machine Learning for Finance* · **Course:** *Data Analysis for Business and Finance* · **Technical writing:** Towards Data Science, HackerNoon and KDnuggets

[Research highlights](./RESEARCH_HIGHLIGHTS_2026.md) · [Research impact](./RESEARCH_IMPACT.md) · [Open-source contributions](./NVIDIA_RAPIDS_CONTRIBUTION.md) · [Industry recognition](./INDUSTRY_RECOGNITION.md)

---

<div align="center">

### Build → Measure → Publish → Improve

**Follow [@sauravsingla](https://github.com/sauravsingla) for releases, benchmarks and reproducible open-source experiments.**

</div>