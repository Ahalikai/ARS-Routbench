# ARS: Automatic Routing Solver with Large Language Models

**Authors:** Kai Li, Fei Liu, Zhenkun Wang, Xialiang Tong, Xiongwei Han, Mingxuan Yuan

## Introduction

Real-world Vehicle Routing Problems (VRPs) are characterized by a variety of practical constraints, making manual solver design both knowledge-intensive and time-consuming. Although there is increasing interest in automating the design of routing algorithms, existing research has explored only a limited array of VRP variants and fails to adequately address the complex and prevalent constraints encountered in real-world situations.

To fill this gap, this repository introduces **ARS (Automatic Routing Solver)**, which employs Large Language Model (LLM) agents to enhance a backbone algorithm framework by automatically generating constraint-aware heuristic code, based on problem descriptions and several representative constraints selected from a database.

## Key Features
- **RoutBench**: A benchmark of 1,000 VRP variants derived from 24 attributes, for evaluating the effectiveness of LLM-based routing solvers in addressing complex constraints.
- **Automatic Constraint Handling**: Automatically generates heuristic code for complex constraints using LLM agents.
- **Performance**: Outperforms state-of-the-art LLM-based methods and commonly used solvers, solving 91.67% of common VRPs and achieving at least a 30% improvement across all benchmarks.

## Citation

If you use this work, please cite our paper:

```
@article{li2025ars,
  title={ARS: Automatic Routing Solver with Large Language Models},
  author={Kai Li, Fei Liu, Zhenkun Wang, Xialiang Tong, Xiongwei Han, Mingxuan Yuan},
  journal={arXiv preprint arXiv:2502.15359},
  year={2025}
}
```

The paper is available on [arXiv](https://arxiv.org/abs/2502.15359v1).

## Version Information

- **Current Version**: v1.0.0
- **Release Date**: Feb 21, 2025

