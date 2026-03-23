# Hi, I'm Alessandro Zuliani

**Applied Mathematician & AI Engineer** specializing in generative models for structured data.

I work on diffusion models, flow matching, and stochastic processes, with a focus on making these methods work on discrete and graph-structured domains where standard continuous approaches break down. Currently also developing a continuous score-based diffusion model inspired by [Riemannian Score-Based Generative Modelling](https://arxiv.org/abs/2203.02923).

Currently AI Engineer at **Davis AI** (Paris). Previously Quant Researcher at **CFM** (Paris).

---

### What I'm working on

**[Discrete Diffusion for Architectural Design](https://github.com/Zullo2000/BD_Generation_Public)** — A masked discrete diffusion model that generates valid residential floorplan graphs with inference-time constraint guidance, achieving 73.5% constraint satisfaction without retraining. Built at Davis AI. 

**[Why Graph Diffusion Breaks Molecules](https://github.com/Zullo2000/why-graph-diffusion-breaks-molecules)** — An empirical and theoretical analysis showing that independent edge noise in discrete graph diffusion is structurally blind: molecular graphs disconnect at t/T ~ 0.08 when 98% of edges are still intact. Proposes structure-aware corruption schedules as a fix.

**[Neural Fokker-Planck Equations](https://github.com/Zullo2000/neural-fokker-planck)** — Learning SDEs from distribution snapshots via deterministic moment dynamics. No SDE simulation, no density estimation, no trajectory tracking — 24x faster than Neural SDEs at comparable accuracy.

---

### Research interests

- Discrete and continuous diffusion models
- Generative models on graphs (molecules, architectures, networks)
- Flow matching and optimal transport
- Stochastic differential equations and Fokker-Planck dynamics
- Constrained generation and inference-time guidance

---

### Tech

Python | PyTorch | JAX | Hydra | W&B | torchsde | torchdiffeq

---

### Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alessandro-zuliani-0b0130186)
