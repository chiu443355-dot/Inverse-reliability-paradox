# Methodology

## Dataset Sources

### DataCo Supply Chain Dataset
- 180,519 records
- multi-country logistics operations

### Delhivery Dataset
- Indian logistics shipment records

### Global Risk Dataset
- supply-chain risk observations (2024–2026)

---

# Analytical Pipeline

## Step 1 — Data Cleaning
- null-value removal
- categorical normalization
- timestamp formatting

## Step 2 — Shipment Classification
Shipments categorized by:
- priority tier
- delay status
- operational region

## Step 3 — Statistical Analysis
Measured:
- late-delivery frequencies
- priority-class divergence
- congestion behavior

---

# Simulation Framework

Monte Carlo simulation used to model:
- stochastic congestion
- overload probability
- queue divergence
- mitigation behavior

---

# Kalman Filtering

Kalman filters were applied to:
- estimate hidden congestion states
- smooth noisy operational signals
- forecast utilization drift

---

# Limitations

- observational datasets
- proxy utilization assumptions
- no live telemetry integration
- simulation-only validation
