# Multimodal-AI-Research

A curated collection of cutting-edge research projects on **multimodal learning**, focused on the integration of diverse data modalities—such as text, images, time series, and more—to tackle complex, real-world challenges.

> **Vision:** Drive reproducible, modular, and scalable multimodal AI experimentation by organizing each research line as an independent, fully contained repository, linked through Git submodules.

---

## 📂 Repository Overview

This **meta-repository** uses **Git submodules** to aggregate multiple, standalone research projects. Each subproject is:

- An independent, fully clonable Git repository.
- Maintained and versioned in isolation.
- Equipped with its own README, environment configuration, and dependencies.
- Focused on a well-defined problem in multimodal AI.

### 🔗 Current Subprojects

- [`anomaly-detection-campaigns`](https://github.com/LucaReggiani-AI-Projects/anomaly-detection-campaigns)  
  *Detect anomalies in marketing campaigns by leveraging and fusing time series, image, and textual data.*  

*(More exciting projects coming soon!)*

---

## 🚀 Quickstart: How to Clone Everything

To **clone this repository together with all submodules** in one shot, run:

```bash
git clone --recurse-submodules https://github.com/LucaReggiani-AI-Projects/Multimodal-AI-Research.git
```
If you already cloned the repo without `--recurse-submodules`, you can initialize and update submodules manually:

```bash
git submodule update --init --recursive
```

This ensures that all subprojects are correctly downloaded and available locally.

## How to Update Submodules
When updates are made to individual submodules, you can fetch the latest changes with:
```bash
git submodule update --remote --merge
```
This will pull any new commits from the linked sub-repositories.

### Why Submodules? 

Using Git submodules offers several advantages:

- **Modularity:** Each project can evolve independently without affecting others.
- **Reusability:** Subprojects can be used in different super-repositories if needed.
- **Scalability:** Adding new research projects is clean and manageable.

---

### Contributions

This repository is designed for personal research and academic exploration. If you have suggestions or improvements, feel free to open an issue or pull request.

---

### Contact

For inquiries, collaborations, or project discussions, feel free to connect:  
[LinkedIn Profile]()  
[Personal Website]()

© 2025 Luca Reggiani. All rights reserved.
---
