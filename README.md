# Training-Free Active Learning with Large Language Models for Materials Discovery

## 📖 Overview

Active learning (AL) enables accelerated materials discovery by prioritizing informative experiments.  
However, conventional machine-learning–based AL methods typically require:

- task-specific feature engineering,
- numerical training data,
- and careful model initialization.

In this work, we introduce a **training-free large language model–driven active learning framework (LLM-AL)** that proposes experiments directly from structured or textual dataset descriptions without model training.

Across multiple materials science benchmarks, LLM-AL:

- reduces experiments required to reach optimal candidates,
- mitigates cold-start limitations,
- and demonstrates competitive or superior performance compared to traditional ML-based AL approaches. 

This repository provides all data and analysis scripts required to reproduce the results and figures reported in the manuscript.

---

## 🧪 Included Datasets

Four heterogeneous materials discovery problems were used to evaluate LLM-guided active learning:

| Dataset | Task | Objective |
|---|---|---|
| **matbench_steels** | Alloy design | Maximize yield strength |
| **P3HT/CNT** | Conductive composites | Maximize conductivity |
| **Perovskite** | Stability screening | Minimize instability index |
| **Membrane** | Polymeric membranes | Maximize elastic modulus |

These datasets span:

- compositional materials design
- experimental processing datasets
- stability prediction
- and polymer membrane optimization

---

## 🤖 Methods Compared

The repository contains trajectories for:

### Large Language Model Active Learning
- **LLM: Parameter-Format**
- **LLM: Report-Format**

### Traditional Machine Learning Active Learning
- Gaussian Process Regression (**GPR**)
- Random Forest Regression (**RFR**)
- XGBoost (**XGB**)
- Bayesian Neural Network (**BNN**)

### Baseline
- Random Walk sampling

Each trajectory records sequential experiment selection during pool-based active learning.

---
This repository contains the **datasets, benchmarking results, and analysis code** accompanying the manuscript:

> **Training-Free Active Learning Framework in Materials Science with Large Language Models**  
> Hongchen Wang*, Rafael Espinosa Castañeda*, Jay R. Werber, Yao Fehlis, Edward Kim, Jason Hattrick-Simpers  
> arXiv:2511.19730 (2025)  
> https://arxiv.org/abs/2511.19730

---
