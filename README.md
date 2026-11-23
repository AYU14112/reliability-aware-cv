# Reliability-Aware Adaptive Computation for Resource-Constrained Computer Vision

## Research Overview

This project investigates reliability-aware adaptive computation for
resource-constrained computer vision systems.

The central research question is whether a vision model can dynamically
adjust its computational depth according to input difficulty and visual
degradation while maintaining reliable predictions.

## Experimental Setup

- Task: Image classification
- Dataset: CIFAR-100
- Robustness evaluation: CIFAR-100-C
- Backbone: ResNet-18
- Framework: PyTorch
- Hardware acceleration: Apple Metal Performance Shaders (MPS)
- Execution: Local-only

## Research Objectives

1. Investigate adaptive inference under visual degradation.
2. Evaluate prediction reliability and calibration.
3. Measure computational cost and inference latency.
4. Compare adaptive inference strategies against fixed-computation baselines.

## Repository Structure

- `src/` — Model implementations and evaluation code
- `scripts/` — Execution scripts
- `configs/` — Experiment configurations
- `notebooks/` — Research notebooks
- `data/` — Local datasets
- `results/` — Experimental outputs
- `papers/` — Literature and research notes

## Status

Environment setup completed. Experimental implementation is pending.

## Execution

All experiments are intended to run locally.
