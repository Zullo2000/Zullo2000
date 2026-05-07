# Hi, I'm Alessandro Zuliani

**Applied Mathematician & AI Scientist** specializing in generative models for structured data.

I work on diffusion models, flow matching, and stochastic processes, with applications to discrete, continuous, and hybrid discrete-continuous domains. Current focus: constrained generation under mixed modalities (categorical + geometric), with inference-time guidance to enforce complex user constraints without retraining.

Currently AI Engineer at **Davis AI** (Paris). Previously Quant Researcher at **CFM** (Paris).

---

### What I've worked on

**[Discrete Diffusion for Constrained Generation: A Literature Review (PDF)](https://github.com/Zullo2000/Zullo2000/releases/latest/download/Literature_Review_Discrete_Diffusion.pdf)**: Literature Review on Discrete Diffusion papers I found useful.

**[Hybrid Discrete-Continuous Diffusion for Architectural Design](https://github.com/Zullo2000/Hybrid_Floorplan_Generation_From_Bubbles_Public)**: Extends the discrete-only model to jointly generate room geometry (DDPM) and room types (MDLM) via a 63.5M-param dual-stream DiT. A three-layer inference guidance stack (CFG + energy + SVDD) pushes constraint satisfaction from 73% to 84.6% on full building floors. Built at Davis AI.

**[Discrete Diffusion for Architectural Design](https://github.com/Zullo2000/BD_Generation_Public)**: A masked discrete diffusion model that generates valid residential floorplan graphs with inference-time constraint guidance, achieving 73.5% constraint satisfaction without retraining. Built at Davis AI. 

**[Why Graph Diffusion Breaks Molecules](https://github.com/Zullo2000/why-graph-diffusion-breaks-molecules)**: An empirical and theoretical analysis showing that independent edge noise in discrete graph diffusion is structurally blind: molecular graphs disconnect at t/T ~ 0.08 when 98% of edges are still intact. Proposes structure-aware corruption schedules as a fix.

**[Neural Fokker-Planck Equations](https://github.com/Zullo2000/neural-fokker-planck)**: Learning SDEs from distribution snapshots via deterministic moment dynamics. No SDE simulation, no density estimation, no trajectory tracking. 24x faster than Neural SDEs at comparable accuracy.

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
