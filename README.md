# QID-OS: Predictive Operating-System Control Layer (Core Simulation & Ablation Framework)

This repository contains the official simulation, RLS correction, and $2^3$ full-factorial ablation study code accompanying the manuscript:
> **"A Predictive Operating-System Control Layer for Quantum Computing Hardware and Execution Stacks"**  
> Submitted to *IEEE Transactions on Quantum Engineering (TQE)* (Manuscript ID: `TQE-26-10-REG-0681`).

## Overview
QID-OS acts as a causal predictive control-plane mediating between hardware telemetry and higher-level execution stacks. This code repository ensures the reproducibility of the numerical evaluations, including:
1. Real-time parameter estimation via Recursive Least Squares (RLS).
2. Full-factorial $2^3$ ablation analysis ($10^5$ trajectories with batch size $B=10$).
3. Distance-3 surface code integration metrics.

## Execution
To run the ablation study script:
```bash
python src/ablation_runner.py
