# Awesome World Action Models (WAM)

A curated list of papers, projects, and resources on **World Action Models (WAMs)** for robot control, planning, and generalization.

This repository focuses on a recent line of work that learns **actions together with future world dynamics**, typically by adapting or leveraging large pretrained **video generation / world modeling** backbones for embodied control.

> Contributions are welcome. Please open a pull request for new papers, code, benchmarks, or corrections.

---

## What are World Action Models?

World Action Models (WAMs) learn the joint structure of:

- **observations / future visual dynamics**
- **robot actions**
- **task-conditioned control**

Compared with standard Vision-Language-Action (VLA) policies, many recent WAM-style methods aim to inherit stronger **physical and temporal priors** from video or world modeling backbones.

Related terms in this area include:

- **WAM** — World Action Model
- **VAM** — Video-Action Model
- **video-first policy learning**
- **action-centered world modeling**
- **causal world modeling for robot control**

---

## Table of Contents

- [Core WAM / VAM Papers](#core-wam--vam-papers)
- [Closely Related Papers](#closely-related-papers)
- [Frequently Cited Foundations](#frequently-cited-foundations)
- [Benchmarks and Datasets](#benchmarks-and-datasets)
- [Code and Project Pages](#code-and-project-pages)
- [Contributing](#contributing)

---

## Core WAM / VAM Papers

### 2026

- **World Action Models are Zero-shot Policies**  
  Seonghyeon Ye, Yunhao Ge, Kaiyuan Zheng, et al.  
  [[arXiv](https://arxiv.org/abs/2602.15922)]

- **Causal World Modeling for Robot Control**  
  Lin Li, Qihang Zhang, Yiming Luo, et al.  
  [[arXiv](https://arxiv.org/abs/2601.21998)]

- **GigaWorld-Policy: An Efficient Action-Centered World-Action Model**  
  [[arXiv](https://arxiv.org/abs/2603.17240)]

- **Cosmos Policy: Fine-Tuning Video Models for Visuomotor Control and Planning**  
  Moo Jin Kim, Yihuai Gao, Tsung-Yi Lin, et al.  
  [[arXiv](https://arxiv.org/abs/2601.16163)] [[project page](https://research.nvidia.com/labs/dir/cosmos-policy/)]

### 2025

- **Motus: A Unified Latent Action World Model**  
  Hongzhe Bi, Hengkai Tan, Shenghao Xie, et al.  
  [[arXiv](https://arxiv.org/abs/2512.13030)] [[project page](https://motus-robotics.github.io/motus)]

- **mimic-video: Video-Action Models for Generalizable Robot Control Beyond VLAs**  
  Jonas Pai, Liam Achenbach, Victoriano Montesinos, et al.  
  [[arXiv](https://arxiv.org/abs/2512.15692)]

---

## Closely Related Papers

These papers are not always framed explicitly as “WAM”, but they are highly relevant to the same research trend.

- **VideoVLA: Video Generators Can Be Generalizable Robot Manipulators**  
  [[arXiv](https://arxiv.org/abs/2512.06963)]

- **Video Generators are Robot Policies**  
  [[arXiv](https://arxiv.org/abs/2508.00795)]

- **Learning to Act from Actionless Videos through Dense Correspondences**  
  [[arXiv](https://arxiv.org/abs/2310.08576)]

- **Genie 2: A Large-Scale Foundation World Model**  
  [[blog / announcement](https://deepmind.google/discover/blog/genie-2-a-large-scale-foundation-world-model/)]

---

## Frequently Cited Foundations

### Robot policy / VLA foundations

- **RT-1: Robotics Transformer for Real-World Control at Scale**
- **RT-2: Vision-Language-Action Models Transfer Web Knowledge to Robotic Control**
- **OpenVLA: An Open-Source Vision-Language-Action Model**
- **ACT: Action Chunking with Transformers**
- **Diffusion Policy: Visuomotor Policy Learning via Action Diffusion**

### World modeling / generative modeling foundations

- **Dreamer**
- **DreamerV2**
- **DreamerV3**
- **UniDiffuser: One Transformer Fits All Distributions in Multi-Modal Diffusion at Scale**
- **Flow Matching for Generative Modeling**

---

## Benchmarks and Datasets

### Benchmarks

- **LIBERO**
- **RoboCasa**
- **RoboTwin 2.0**

### Datasets / training sources often mentioned in this literature

- **OXE / Open X-Embodiment**
- **DROID**
- **AgiBot**
- **RoboMind**

---

## Code and Project Pages

- **Cosmos Policy** — project page / paper / code / models
- **Motus** — project page / official code
- Add more official repositories as they are released.

---

## Suggested Taxonomy for Future Additions

When adding papers, consider tagging them with one or more of the following:

- `WAM`
- `VAM`
- `video backbone`
- `latent action`
- `flow matching`
- `diffusion policy`
- `planning`
- `cross-embodiment`
- `zero-shot control`
- `real-world robotics`

---

## Contributing

Please keep entries concise and use the following format:

```text
- **Paper Title** — Authors, Year. [paper] [code] [project]
