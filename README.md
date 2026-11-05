# Hi! I'm An 👋

I'm an Assistant Professor at [VinUniversity](https://vinuni.edu.vn/people/le-thai-an/), a Visiting Professor at [IAS, TU Darmstadt](https://www.ias.informatik.tu-darmstadt.de/Team/AnThaiLe), and Director of Foundation AI at [VinRobotics](https://vinrobotics.net/), where my team works on the RL stack for high-payload humanoid locomotion, humanoid VLA architectures and training recipes, and the model optimization and edge-deployment toolchain.

I study how robots can plan, learn, and act reliably with **limited computation and data**. My group works on three directions that increasingly fit together:

- **Parallel planners.** We represent candidate plans and their costs as tensors so GPUs can search many of them at once (*tensor search*), and pair this structure with optimal transport and diffusion / flow-matching priors for long-horizon, multimodal, non-convex problems.
- **Scaled-down robot foundation models.** VLA policies that adapt from fewer demonstrations, using built-in symmetries and future observations as supervision, and that run on affordable onboard computers: layer pruning, native low-bit quantization, a C++ inference runtime, and shared SIMD kernels that run policies on CPUs down to a Raspberry Pi 5.
- **Whole-body control through contact.** Force-aware controllers that let 70 to 85 kg humanoids respond to contact and changing payloads with their arms, torso, and legs together, plus behavior spaces that transfer across humanoid bodies.

Next up: bringing these together, with whole-body VLAs trained on contact-rich data, planners checking their actions, and compliant controllers executing them, all within the robot's compute budget.

On weekends, I write JAX/PyTorch simulators for curved spacetimes (Kerr black holes, the Penrose process, warp-drive energy conditions), because these physics are art!

## Selected papers

### Planning & Search
- [**Model Tensor Planning**](https://openreview.net/forum?id=fk1ZZdXCE3), TMLR 2025 / ICLR 2026 (J2C) · [code](https://github.com/anindex/mtp)
- [**Global Tensor Motion Planning**](https://sites.google.com/view/gtmp/home), IEEE RA-L 2025 / ICRA 2026 · [code](https://github.com/anindex/gtmp)
- [**Anytime Global Tensor Motion Planning**](https://arxiv.org/abs/2608.25830), under review · [code](https://github.com/CoMMALab/anytime_gtmp)
- [**Motion Planning Diffusion**](https://sites.google.com/view/motionplanningdiffusion), IEEE T-RO 2025 / AAAI 2026 (journal track) / IROS 2023 · [code](https://github.com/joaoamcarvalho/mpd-splines-public)
- [**Accelerating Motion Planning via Optimal Transport**](https://sites.google.com/view/sinkhorn-step/), NeurIPS 2023 · [code](https://github.com/anindex/mpot)
- [**CLOT: Multi-Robot Motion Planning via Collaborative Optimal Transport under STL Tasks**](https://mengguo.github.io/personal_site/papers/pdf/zhang2026clot.pdf), ICRA 2026

### Efficient Robot Foundation Models
- [**FoldQuantVLA: Native Low-Bit Quantization of Vision-Language-Action Models via Consistent Folding**](https://arxiv.org/abs/2609.24433), preprint · [code](https://github.com/cair-vinuni/FoldQuantVLA)
- [**vla.simd: Efficient CPU Inference for Language-Conditioned Manipulation**](https://arxiv.org/abs/2609.24274), preprint · [project](https://vla-simd.github.io/) · [code](https://github.com/cair-vinuni/vla.simd)
- [**vla.cpp: A Unified Inference Runtime for Vision-Language-Action Models**](https://arxiv.org/abs/2606.08094), under review · [code](https://github.com/VinRobotics/vla.cpp)
- [**FOCA: Future-Oriented Conditioning for Data-Efficient Vision-Language-Action Adaptation**](https://focavla.github.io/), ICML 2026 · [code](https://github.com/cair-vinuni/FOCA)
- [**Start Right, Arrive Right: Asynchronous Execution via Initial Noise Selection**](https://paint-action-chunking.github.io/), CoRL 2026 · RSS 2026 Diff4RL Workshop (spotlight)
- [**Finetuning Vision-Language-Action Models Requires Fewer Layers Than You Think**](https://clpvla.github.io/), under review · [code](https://github.com/cair-vinuni/CLP_VLA)
- [**EquiVLA: A General Framework for Rotationally Equivariant Vision-Language-Action Models**](https://equivla.github.io/), under review
- [**Retrieve to Act: Motion Primitive Graph Retrieval for Robust VLA Execution**](https://retrieve2act.github.io/r2a/), preprint

### Humanoid Control
- [**CompliantWBC: Whole-Body Compliance for Heavy Humanoids via Force Latent Estimation and Residual Impedance Targets**](https://compliantwbc.github.io/), under review
- [**CrossBFM: Distilling a Shared Latent Behavior Space Across Humanoid Embodiments**](https://dotandung.github.io/crossbfm/), under review · CoRL 2026 Pretrain-to-Adapt Workshop (oral)
- [**TACT-ful: Multi-Channel Terrain Affordance and Compliance Training for Payload-Robust Perceptive Humanoid Locomotion**](https://arxiv.org/abs/2606.20645), under review
- [**γ₀: A Generalist Policy for Multi-Embodiment Motion Control**](https://gamma-zero.com/), ongoing project · [playground](https://play.gamma-zero.com/)
- [**DoublyAware: Dual Planning and Policy Awareness for Temporal Difference Learning in Humanoid Locomotion**](https://doi.org/10.1109/LRA.2025.3648611), IEEE RA-L 2026

### Machine Learning
- [**Training Non-Differentiable Networks via Optimal Transport**](https://openreview.net/forum?id=8mlcqTTMuU), TMLR 2026 · [code](https://github.com/anindex/polystep)
- [**AAC: Admissible-by-Architecture Differentiable Landmark Compression for ALT**](https://arxiv.org/abs/2604.20744), TMLR 2026 · [code](https://github.com/anindex/aac)

### Numerical Physics (GR)
- [**Rarity of rocket-driven Penrose extraction in Kerr spacetime**](https://doi.org/10.1103/f3jn-7wcp), Physical Review D 2026 · [code](https://github.com/anindex/penrose_process)
- [**Observer-robust energy condition verification for warp drive spacetimes**](https://doi.org/10.1088/1361-6382/aeb25a), Classical and Quantum Gravity 2026 · [code](https://github.com/anindex/warpax)

Full list on [my website](https://anindex.github.io/#publications) and [Google Scholar](https://scholar.google.com/citations?user=k0r0tfUAAAAJ).

## Links
- 🌐 Website: [anindex.github.io](https://anindex.github.io/)
- 🎓 Google Scholar: [An Thai Le](https://scholar.google.com/citations?user=k0r0tfUAAAAJ)
