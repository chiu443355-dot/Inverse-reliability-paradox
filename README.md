# Inverse Reliability Paradox (IRP)

Research framework analyzing congestion-driven priority failure behavior in logistics systems using queueing theory, stochastic modeling, and predictive simulation.

---

# Overview

The Inverse Reliability Paradox (IRP) describes a counterintuitive logistics phenomenon where premium-priority shipments may fail at rates comparable to or worse than standard shipments under overloaded operational conditions.

This repository contains:
- the IRP 2026 research paper
- simulation notebooks
- statistical analyses
- congestion modeling experiments
- queueing theory implementations
- MLK predictive mitigation framework experiments

---

# Research Questions

- Why do high-priority shipments fail under overloaded logistics networks?
- Can congestion thresholds mathematically explain priority degradation?
- Can predictive infrastructure reduce priority leakage?

---

# Key Concepts

- Queueing Theory
- M/M/1 Systems
- Heavy-Traffic Approximation
- Kalman Filtering
- Congestion Forecasting
- Monte Carlo Simulation
- Reliability Degradation Modeling

---

# Repository Structure

```text
inverse-reliability-paradox/
│
├── paper/
├── datasets/
├── notebooks/
├── figures/
├── docs/
├── equations/
└── requirements.txt
```

---

# Datasets

## Included Sources
- DataCo Global Supply Chain Dataset
- Delhivery Logistics Dataset
- Global Supply Chain Risk Dataset

All datasets were obtained from publicly available research or Kaggle sources.

---

# Core Findings

Observed simulations and dataset analyses suggest:
- premium shipping classes may exhibit elevated late-delivery behavior under high utilization
- overload states can produce nonlinear reliability collapse
- predictive congestion mitigation may reduce priority leakage

The framework remains observational and simulation-based.

---

# MIMI Logic Kernel (MLK)

The MLK framework is an experimental congestion prediction architecture designed to:
- forecast overload conditions
- estimate queue saturation
- predict shipment instability
- simulate mitigation behavior

---

# Development Metrics

- 173+ commits
- 140+ deployments
- 100M+ simulated analyses
- Built independently with ₹0 funding

---

# Research Status

- Independent research project
- Under academic review
- Simulation validated
- No live production deployment

---

Implementation Software

The production implementation of the MIMI Logic Kernel (MLK) and SITI Intelligence platform is available at:

https://github.com/chiu443355-dot/SITI-GSC-KERNEL

---

# License

MIT License
